# Prompt/Image Generator (v2.1.6)

The **Prompt Generator** is a Python-based application that allows users to create, save, and manage creative prompts for generating art or writing. Designed to integrate seamlessly with popular AI tools like Stable Diffusion or DALL-E, this tool includes a user-friendly interface for prompt generation, history tracking, and image rendering.

---

## Features

### Prompt Creation and Management

- **Custom Prompt Generation**: Create prompts based on user-defined topics, styles, and additional details.
- **Random Prompts**: Generate random prompts for inspiration.
- **Popular Prompts**: Access trending prompts from the Reddit Writing Prompts community.

### Image Integration

- **Image Generation**: Send generated prompts to an AI art model for immediate rendering.
- **Regeneration**: Easily reload and tweak prompts to generate variations of the same image.
- **Image Sharing**: Share generated images on platforms like Twitter, Facebook, Reddit, Discord, Instagram, and Pinterest.

### History and Saving

- **Prompt History**: Automatically logs your prompt history in an Excel file for easy reference.
- **Saved Prompts**: Save your favorite prompts to a dedicated file for reuse.

### User-Friendly Interface

- **GUI Interface**: Built with PySimpleGUI for intuitive interaction.
- **Social Media Integration**: Share your creations effortlessly.
- **Ratings and Feedback**: Provide ratings and reviews directly in the app.

---

## How to Use

1. **Run the Program**:

   ```bash
   python prompt_generator.py
   ```

2. **Generate Prompts**:

   - Fill in the "Topic," "Style," and "Other" fields, then click **Submit**.
   - Or, use the **Random Prompt** or **Popular Prompt** buttons for automatic suggestions.

3. **View and Save**:

   - Use **View History** to open a log of previous prompts.
   - Save preferred prompts using the **Save** button.

4. **Generate Images**:

   - After creating a prompt, click **Generate Image**.
   - Review, save, or share the generated images using the buttons provided.

---

## Requirements

- Python 3.x
- Required Libraries:
  ```bash
  pip install PySimpleGUI praw openai openpyxl replicate pillow
  ```

---

## Recommendations

- **Prompt Creation**:
  - For best results, use concise and descriptive inputs in the "Topic" and "Style" fields.
- **Image Generation**:
  - Ensure a stable internet connection for AI model interaction.

---

## Installation

1. Install Python 3.x from [python.org](https://www.python.org/).
2. Clone or download this repository.
3. Install the required libraries using the commands listed above.
4. Run the program using the `python` command.

---

## Support

For questions, issues, or feature requests, please contact [DonghyunWon2@gmail.com](mailto\:DonghyunWon2@gmail.com).

---

## Future Enhancements

- Expand support for other AI art platforms.
- Batch processing for multiple prompts.
- Improved error handling and user feedback.

---

