# Image Processing Application

A web-based image processing tool built with Django, offering a range of image editing features. This application allows users to upload images, editing and download image.

## Features

- **Image Upload**: Upload images directly from your device.
- **Image Processing**: Resize, crop, rotate, and apply filters.
- **Edit History**: Track your previous edits and revert changes.
- **Image Management**: View and organize uploaded images.

## Project Structure

```
Image-Processing-Application/
├── gallery/               # Main Django app
├── image_site/            # Django project config and settings
├── media/                 # Uploaded image storage
├── manage.py             
├── requirements.txt       
└── README.md              
```

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ChrisChln/Image-Processing-Application.git
cd Image-Processing-Application
```

### 2. Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Migrations

```bash
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000 in your browser to start using the app.

## Usage

1. Upload an image from your local device.
2. Edit it with tools like crop, rotate, or apply filters.
3. Review and manage your image history or revert changes as needed.

## Contributing

Pull requests are welcome. If you'd like to suggest features or report bugs, please open an issue or submit a PR.




---
