# Responsive Codeforces Contest Table

This project is a web-based application that displays Codeforces contest problems in a responsive table format. Users can enter their Codeforces handle to track their problem-solving progress. The table highlights solved, wrong-answer, and time-limit-exceeded problems using different colors.

## Features
- Fetches and displays Codeforces contest data using the Codeforces API.
- Displays a responsive and sortable table of contests and problems.
- Highlights problem-solving status:
  - **Green** for solved problems.
  - **Red** for wrong answers.
  - **Yellow** for time-limit exceeded.
- Allows filtering contests by division (Div. 1, Div. 2, etc.).
- Users can set a handle to track their own submissions.
- Saves user handle in cookies for persistent session tracking.

## Technologies Used
- **HTML**: Structuring the webpage.
- **Bootstrap 5**: Styling and responsive design.
- **JavaScript**: Fetching and processing Codeforces API data.
- **Codeforces API**: Retrieving contest, problem, and user submission data.

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/2077DevWave/CF-list.git
   ```
2. Open `index.html` in a web browser.
3. Enter your Codeforces handle to see your progress.

## How It Works
1. The webpage fetches a list of recent Codeforces contests.
2. For each contest, it fetches the problem list.
3. When a user enters a handle, the script fetches their submission data.
4. The table is dynamically updated with problem statuses.
5. Data is cached locally using cookies and `localStorage`.

## Future Improvements
- Add pagination for large datasets.
- Improve UI for better user experience.
- Implement additional filters for problem difficulty levels.

## License
This project is licensed under the MIT License.

