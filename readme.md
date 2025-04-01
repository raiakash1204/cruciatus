# Cruciatus

Cruciatus is an AI-based math solver that detects handwritten mathematical equations and provides step-by-step solutions to the problems.

## Features

- **Handwritten Equation Recognition**: Accurately detects and interprets handwritten mathematical expressions.
- **Step-by-Step Solutions**: Provides detailed explanations for each step in solving the detected equations.
- **User-Friendly Interface**: Simple and intuitive interface for ease of use.

## Installation

To set up Cruciatus on your local machine:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/raiakash1204/cruciatus.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd cruciatus
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Application**:

   ```bash
   python app.py
   ```

2. **Access the Web Interface**:

   Open your web browser and navigate to `http://localhost:5000`.

3. **Upload an Image**:

   Upload an image containing a handwritten mathematical equation.

4. **View Solution**:

   The application will process the image and display a step-by-step solution to the equation.

## Project Structure

- `app.py`: Main application file that runs the Flask server.
- `templates/`: Contains HTML templates for the web interface.
- `static/uploads/`: Directory where uploaded images are stored.
- `requirements.txt`: Lists the Python dependencies required for the project.

## License

This project is licensed under the MIT License.

---

*Note: This README is generated based on the available information from the repository. For more detailed documentation and updates, please refer to the [Cruciatus GitHub repository](https://github.com/raiakash1204/cruciatus).*