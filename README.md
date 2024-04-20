
# Fitness React App

This is a dynamic fitness application built using React.js, integrating the ExerciseDB API from RapidAPI to fetch exercise data. The app utilizes Material-UI for styled components, including a search page, detailed exercise pages, and pagination for better navigation and user experience.

## Features

- **Dynamic Exercise Data**: Utilizes the ExerciseDB API from RapidAPI to fetch a wide range of exercise data, categorized by body parts.
- **Material-UI Styling**: Enhances the UI with modern and responsive components from Material-UI, providing a sleek and intuitive user interface.
- **Search Page**: Allows users to search for specific exercises or filter exercises by body parts, providing a seamless browsing experience.
- **Detailed Exercise Pages**: Provides detailed information about each exercise, including instructions, images, and targeted muscle groups, aiding users in understanding and performing exercises correctly.
- **Pagination**: Implements pagination to display exercises in manageable chunks, enhancing performance and user navigation.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/as4c/fitness-app.git
```

2. Navigate to the project directory:

```bash
cd fitness-app
```

3. Install dependencies:

```bash
npm install
```

4. Create a `.env` file in the root directory and add your RapidAPI key:

```bash
REACT_APP_RAPIDAPI_KEY=your_rapidapi_key_here
```

## Usage

1. Start the development server:

```bash
npm start
```

2. Open your browser and navigate to `http://localhost:3000` to view the app.

3. Explore different exercises, search for specific exercises, and navigate through pages using the pagination controls.

## Dependencies

- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Material-UI](https://mui.com/): React components for faster and easier web development.
- [RapidAPI](https://rapidapi.com/): A platform that allows developers to discover, test, and connect to APIs.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Special thanks to RapidAPI for providing access to the ExerciseDB API.
- Material-UI for their excellent UI components and documentation.

---
