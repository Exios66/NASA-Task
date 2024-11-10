# NASA-Task

## Description

The NASA Task Load Index (NASA-TLX) is a widely used assessment tool that rates perceived workload in order to assess a task, system, or team's effectiveness or other aspects of performance. This implementation provides a web-based version of the NASA-TLX assessment.

The tool measures workload on six different subscales:

- **Mental Demand**: How much mental and perceptual activity was required? Was the task easy or demanding, simple or complex?
- **Physical Demand**: How much physical activity was required? Was the task easy or demanding, slack or strenuous?
- **Temporal Demand**: How much time pressure did you feel due to the pace at which tasks occurred? Was the pace slow or rapid?
- **Performance**: How successful were you in performing the task? How satisfied were you with your performance?
- **Effort**: How hard did you have to work (mentally and physically) to accomplish your level of performance?
- **Frustration**: How irritated, stressed, and annoyed versus content, relaxed, and complacent did you feel during the task?

The assessment consists of two parts:

1. Rating each dimension on a scale of 0-100
2. Weighted scoring through pairwise comparisons of the dimensions

The final score provides both unweighted and weighted workload scores that can be used to assess and compare task difficulty.

## Features

- Clean, intuitive web interface
- Dark mode support for reduced eye strain
- Real-time slider inputs for dimension ratings
- Comprehensive pairwise comparisons
- Automatic score calculation
- Responsive design for various screen sizes

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/NASA-Task.git
   ```

2. Open `index.html` in your web browser

3. Complete the assessment:
   - Rate each of the six dimensions using the sliders (0-100)
   - Click "Next" to proceed to the pairwise comparisons
   - For each pair, select which factor contributed more to the workload
   - Click "Calculate Score" to view your results

4. Review your results:
   - Unweighted Score: Simple average of all ratings
   - Weighted Score: Adjusted based on the pairwise comparison weights

5. Use the "Reset" button to start a new assessment

## Implementation Notes

- Pure HTML, CSS, and JavaScript implementation
- No external dependencies required
- Follows the official NASA-TLX methodology
- Includes input validation to ensure complete responses

## References

- Hart, S. G., & Staveland, L. E. (1988). Development of NASA-TLX (Task Load Index): Results of empirical and theoretical research. In P. A. Hancock and N. Meshkati (Eds.) Human Mental Workload. Amsterdam: North Holland Press.
