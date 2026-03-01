# Course Template Structure

This directory serves as a template for creating new courses. It contains a simplified structure mirroring the "The Complete In Silico Drug Discovery Bootcamp" course.

## Directory Structure

- `course template/`
  - `module_manifest.json`: Configuration file defining the course structure, modules, and lessons.
  - `course.json`: Metadata for the course (title, description, author, etc.).
  - `index.md`: Main index file for the course documentation.
  - `landing.html`: HTML template for the course's landing page, including sections for course overview, target audience, learning outcomes, and testimonials.
  - `static/`: Directory for static assets such as images, CSS, and JavaScript files used in `landing.html` and course modules.
  - `module one/`: Directory for the first module's content.
    - `content.md`: Text content for the module.
    - `quiz.html`: HTML file for module assessments.
    - `study_guide.md`: Markdown file for study guides.
    - `presentation.pptx`: PowerPoint presentation file.
    - `video.mp4`: Video file for lessons.
    - `document.pdf`: PDF document for additional resources.
    - `assessment.json`: JSON file containing quiz questions and answers.

## Usage

1. Copy the `course template` directory and rename it to your new course name.
2. Update `module_manifest.json` with your course title and module details.
3. Replace the placeholder files in `module one` (and subsequent modules) with your actual course content.
4. Add more modules as needed by creating new directories and updating `module_manifest.json`.
