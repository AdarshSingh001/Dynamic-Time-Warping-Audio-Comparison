# Piano Performance Evaluation Using Dynamic Time Warping (DTW)

This project is designed for educational purposes to help music students evaluate the accuracy of their piano performances. By comparing a student's played audio to the original piano audio, the system provides a score that reflects how closely the student's performance matches the original. This feedback mechanism aids students in improving their piano lessons by highlighting areas of their performance that may require more practice.

## Features

- **Performance Comparison**: Utilizes Dynamic Time Warping (DTW) to compare a student's piano audio with the original recording, measuring the similarity between the two.
- **Accuracy Scoring**: Provides an accuracy score based on the alignment of the student's performance with the original, helping students understand their strengths and areas for improvement.
- **Audio Feature Extraction**: Processes and extracts key features from the audio, such as pitch contours, to enhance the comparison's precision.
- **Interactive Analysis**: Implemented in a Jupyter Notebook format, allowing for easy modification, experimentation, and visualization of results.

## Installation

To set up the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/AdarshSingh001/Piano_Performance_Evaluation.git
    cd Piano_Performance_Evaluation
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Open the Jupyter Notebook**: Start by opening the provided Jupyter notebook (`Dynamic_Time_Warping_Audio_comparison.ipynb`).

    ```bash
    jupyter notebook Dynamic_Time_Warping_Audio_comparison.ipynb
    ```

2. **Prepare Audio Files**: Ensure you have both the original piano lesson audio and the student's performance audio files in the appropriate format (e.g., WAV).

3. **Run the Cells**: Execute the cells in the notebook sequentially. The notebook includes code to load the audio files, perform the comparison using DTW, and visualize the results.

4. **Analyze the Results**: The notebook will output an accuracy score and visualizations that illustrate the alignment between the original and the student's performance. These results can be used to identify areas where the student can improve.

## Example

Here's a brief overview of what the notebook covers:

- **Loading Audio Files**: Load the original and student audio files for comparison.
- **Feature Extraction**: Extract relevant features (e.g., pitch contours) from the audio files.
- **DTW Comparison**: Use Dynamic Time Warping to align and compare the two performances.
- **Scoring**: Calculate a score based on the alignment, providing feedback on the performance accuracy.
- **Visualization**: Visualize the alignment and discrepancies between the two audio tracks.

## Applications

- **Music Education**: Ideal for use in music schools and online learning platforms where students can receive automated feedback on their piano performances.
- **Self-Learning**: Students practicing independently can use this tool to assess their progress and identify areas for improvement.

## Contribution

This project was created with the intent of enhancing music education through technology. Contributions and suggestions are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This `README.md` file aligns with the fact that your project is in the Jupyter notebook format, allowing users to interactively run and explore the code. If you have any specific sections or details you'd like to add or modify, just let me know!
