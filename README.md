# Lakeview Patient Portal

An accessible patient portal for a hospital, where patients can book appointments, view lab reports, and access their medical history.

## Features

- **Home dashboard:** a summary of the next appointment, latest lab result, and today's medicines
- **Appointments:** book and review appointments
- **Lab reports:** view test results with clear status indicators
- **Medical history:** access past conditions, treatments, and records

## Accessibility

Accessibility was a core goal of this project. It includes:

- A "Skip to main content" link for keyboard and screen reader users
- Semantic HTML landmarks (`header`, `nav`, `main`, `section`)
- ARIA labels and `aria-current` to show the active page in navigation
- An emergency banner on every page with a one-tap call link
- Status badges that don't rely on colour alone
- Atkinson Hyperlegible, a typeface designed for readability
- Proper `<time>` elements for dates
- A responsive layout that works on phones and desktops

## Built With

- HTML5
- CSS3

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/raimiobed/Medical-history.git
   ```
2. Open the folder and double-click `index.html` to view it in your browser.

No installation or build step is needed.

## Project Structure

```
├── index.html            # Home dashboard
├── appointments.html     # Book and manage appointments
├── lab-reports.html      # Lab results
├── medical-history.html  # Medical history records
└── styles.css            # Shared styles
```

## Note

All patient names, numbers, and medical data in this project are fictional sample data created for demonstration purposes.

## Author

**Raimi Obed**
GitHub: [@raimiobed](https://github.com/raimiobed)