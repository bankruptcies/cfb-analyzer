# College Football Analyzer

A Python-based college football analytics tool that allows users to input a team, season year, and week number to retrieve detailed game information using a sports API.

## Features

- User inputs:
  - Team name
  - Season year
  - Week number
  - API key
- Displays:
  - Game matchup
  - Leading passer
  - Leading rusher
  - Leading receiver
  - Team conferences
  - Game ownership information
- Handles invalid user input and missing game data gracefully
- Uses live API data

## Technologies Used

- Python
- REST API
- JSON parsing
- Error handling

## Example Usage

```bash
Enter team: Michigan
Enter year: 2023
Enter week: 5
Enter API key: ********
```

Example Output:

```bash
Michigan vs Nebraska

Leading Passer:
J.J. McCarthy - 250 Yards

Leading Rusher:
Blake Corum - 120 Yards

Leading Receiver:
Roman Wilson - 95 Yards
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/college-football-analyzer.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the program:

```bash
python main.py
```

## Future Improvements

- GUI dashboard
- Streamlit web app
- Data visualizations
- Season statistics analysis
- Team comparison tools
