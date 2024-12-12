# **Animes Search Engine**

Welcome to **Animes Search Engine**!  
This project is designed to help users find their favorite anime with ease and efficiency. Whether you're a casual fan or a dedicated otaku, this search engine simplifies the process of discovering and exploring anime titles.

---

## **Features**

- 🔍 **Advanced Search**: Quickly find anime titles by name, genre, or year.
- 🖼️ **Rich Media**: Displays images, descriptions, and ratings for anime.
- 🎯 **Efficient Scraping**: Leverages powerful tools to fetch anime data from various sources.
- 📊 **Category Sorting**: Browse anime by categories such as action, romance, or fantasy.

---

## **Folder Structure**

### Project Root
- **`animes_data/`**: Contains raw data and datasets used in the project.
- **`animescraper/`**: The backend service for scraping anime information.
- **`back anime app/`**: Backend application for managing APIs and server-side logic.
- **`front anime app/`**: Frontend application for user interactions and visuals.
- **`pdf_transformer/`**: Handles PDF transformations.
- **`search_engine/`**: Core search engine logic.

---

## **Installation**

- **Node.js** (for frontend development)
- **Python** (for search API and scraping)
- **Java** (for backend)
- **Jupyter** (for data analysis and visualization)
- **Database**: (MySQL)
- **Postman**: (to laod data to the database)
- **Git**: To clone the repository

### **Steps**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/AyoubAmqicher/animes-search-engine.git
   cd animes-search-engine
2. **Run the Search Engine API**:
  - Navigate to the search_engine folder.
  - Open search_api.ipynb in Jupyter Notebook.
  - Run all the cells in the notebook. Once completed, a service will start listening on port 8000.
3. **Clone the backend repository**:
  ```bash
   git clone https://github.com/Khadija-Laamiri/searchEngineForAnime-api.git
  ```
4. **Run the backend**:

   - in application.yml insure your database informations are correct :
     
    ![image](https://github.com/user-attachments/assets/be40ec23-69ba-4af7-a59a-058ccc843bcf)

   
  - in your favourite IDE run the main function in SearchEngineForAnimeApiApplication class.
    
    ![image](https://github.com/user-attachments/assets/7bd90d76-1081-46ef-b763-9aa19fe51f40)

  - use postman to create a request to the endpoint import data(you will find the data in the folder animes_data under the name animes_data.json).
    
![image](https://github.com/user-attachments/assets/ee6979ba-4792-403c-b52a-8847668c50f5)

  !!!!! make sure you copy the right path !!!!!
  
5. **Clone the front repository**:

    ```bash
   git clone https://github.com/Enami-FatimaZahrae/searchEngineForAnime-front.git
    ```
6. **run the front**:

   - run npm install inside the directory to run all the depensencies.
    ```bash
   npm install
    ```
  - execute the command  npm run dev to build the project :
    ```bash
     npm run dev
    ```
