

# Image Captioner App 📸

Generate creative, platform-specific captions for your images using the Gemini API. This app leverages Hugging Face for seamless deployment and ease of access.

## Description

The Image Captioner App is designed to create **positive and engaging captions** tailored to specific social media platforms. Simply upload an image, choose your platform, specify the number of captions you need, and let the app do the rest!

## Features

- **Image Upload**: Supports `.jpg`, `.jpeg`, and `.png` file formats.
- **Platform-Specific Captions**: Generate captions for platforms like Instagram, Facebook, Twitter, and more.
- **Customizable Output**: Choose the number of unique captions to generate.
- **Responsive UI**: Built with Streamlit for an interactive and user-friendly interface.

## Tech Stack

**Client**: Streamlit  
**Server**: Hugging Face Spaces (for deployment)  
**API**: Gemini API by Google  

## Installation

Install the project locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/image-captioner-app.git

# Navigate to the project directory
cd image-captioner-app

# Install dependencies
pip install -r requirements.txt
```

## API Reference

### Generate Captions

Use the Gemini API to generate captions for a specific platform based on an uploaded image.



| Parameter     | Type     | Description                                                       |
| :------------ | :------- | :---------------------------------------------------------------- |
| `platform`    | `string` | **Required**. Name of the platform (e.g., Instagram, Facebook).   |
| `image`       | `bytes`  | **Required**. Image data for caption generation.                  |
| `num_captions`| `integer`| **Optional**. Number of captions to generate (default: 1).        |

## Usage

1. **Upload an Image**: Select an image in `.jpg`, `.jpeg`, or `.png` format.
2. **Choose a Platform**: Pick the social media platform for the captions.
3. **Select Caption Count**: Specify how many captions you want.
4. **Generate Captions**: Click the "Generate Captions" button to view the results.
5. **Copy Captions**: Copy your generated captions with a single click.

## Deployment

Deploy this project on **Hugging Face Spaces**:

1. **Setup Repository**:
   - Create a new repository on Hugging Face Spaces: [Hugging Face Spaces](https://huggingface.co/spaces).
   - Clone your repository locally.

   ```bash
   git clone https://huggingface.co/spaces/tushargandhi77/image-captioner-app
   ```

2. **Add Files**:
   - Copy all your project files into the cloned repository.

3. **Push Changes**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push
   ```

4. **Run on Spaces**:
   - Your app will automatically be deployed and accessible via the Hugging Face Spaces URL.

## Deployment Commands

Deploy locally for development:

```bash
streamlit run app.py
```

Push updates to Hugging Face Spaces:

```bash
git add .
git commit -m "Update app"
git push
```

## Example

Below is an example workflow:

1. Upload an image:


2. Choose a platform and generate captions:


3. View and copy your captions:


![image](https://github.com/user-attachments/assets/3d2c9295-9523-4df4-80b4-1ec7e99045d1)
![image](https://github.com/user-attachments/assets/418f3429-06b8-473a-bdb5-07061e657bd4)
![image](https://github.com/user-attachments/assets/75cee69f-eabd-4a99-9648-4a0680b596a0)

