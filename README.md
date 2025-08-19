This is a React-based portfolio project showcase where users can explore projects categorized into Static, Responsive, and Dynamic. The UI updates dynamically using React State to display the relevant projects for the selected category.

🚀 Features

Built with React Functional Components

Uses React State for category switching

Three categories of projects:

Static → Simple informational websites

Responsive → Mobile-friendly & adaptive websites

Dynamic → Interactive applications with user inputs

Clean and modern UI design

Project cards include:

Thumbnail/Image

Project Title

Short description

🛠️ Technologies Used

React (Functional Components + useState hook)

CSS / Tailwind (for styling & responsiveness)

JavaScript (ES6+)

📂 Project Structure
src/
│── components/
│    ├── Projects.js   # Main component with state handling
│    ├── ProjectCard.js # Reusable card component
│
│── assets/
│    ├── images/       # Project images
│
│── App.js             # Root file
│── index.js           # Entry point

🔑 How It Works

By default, the Responsive category is selected.

Clicking on Static / Responsive / Dynamic updates the state using React’s useState.

The UI re-renders the project cards based on the current state.

📸 Example Projects

VR Website → Explore AR/VR industry products

Food Munch → A user-centric food tech website

Portfolio → Personal portfolio to showcase skills

⚡ Installation & Usage
# Clone the repository
git clone https://github.com/yourusername/projects-display.git

# Navigate to folder
cd projects-display

# Install dependencies
npm install

# Run development server
npm start

🌟 Future Enhancements

Add project detail pages with live demos & GitHub links

Dark mode support

Animations for smoother transitions
