# ADMIN-Dashboard
Overview
This project is an Admin Dashboard built with React. It features a responsive layout with a toggleable sidebar for navigation and a main content area.

Features
Header Component: Displays the top navigation bar with a sidebar toggle button.
Sidebar Component: Provides navigation options and can be toggled open or closed.
Home Component: Represents the main content area of the dashboard.
Responsive Layout: Utilizes a grid container to ensure proper layout and responsiveness.
Components
App: The main component that manages the state of the sidebar and renders the Header, Sidebar, and Home components.
Header: Contains the logic to open/close the sidebar.
Sidebar: Displays navigation options and responds to sidebar toggle state.
Home: Represents the main area of the dashboard.
Code Explanation
State Management: The openSidebarToggle state is used to control the visibility of the sidebar. The OpenSidebar function toggles this state.
Event Handling: The OpenSidebar function is passed as a prop to both the Header and Sidebar components for sidebar control.
