## News Aggregator Web App
A responsive news aggregation web application that fetches and displays real-time news articles based on user-selected categories and search queries.
The application focuses on clean UI, dynamic content rendering, and efficient API integration.

## Features
- Real-time news fetching using an external news API  
- Category-based navigation (IPL, Finance, Politics)  
- Keyword-based news search functionality  
- Responsive and user-friendly interface  
- Clickable news cards redirecting to full articles  
- Fallback handling for missing images and descriptions
 
## Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **API:** GNews API  
- **Tools:** VS Code, Live Server
  
## ⚙️ How to Run Locally
> **Note:** This project is designed to run in a local development environment due to third-party API access restrictions.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
2. Open the project folder in Visual Studio Code
3. Right-click on index.html
4. Select “Open with Live Server”
5. The application will open in your browser at:
   http://127.0.0.1:5500/

## Deployment Note
This application works correctly when run locally.
Public deployment on static hosting platforms (such as GitHub Pages) may be restricted due to third-party API security and CORS policies.

## Future Enhancements
1.Integrate a backend proxy to securely manage API requests
2.Add pagination and infinite scrolling
3.Improve error handling and loading indicators
4.Deploy using a full-stack architecture
