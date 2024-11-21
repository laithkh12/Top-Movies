# 🎥 Movie Collection Manager

Manage your favorite movies with ease using **Movie Collection Manager**! This Flask application allows you to add, rate, review, and organize movies in a sleek, user-friendly interface. 🌟

---

## 🚀 Features
- **Add Movies**: Search for movies using the TMDB API and add them to your collection.
- **Rate & Review**: Share your thoughts and ratings for each movie.
- **Dynamic Rankings**: Movies are ranked dynamically based on their ratings.
- **Edit or Delete**: Modify or remove movies effortlessly.
- **Responsive Design**: Built with Flask-Bootstrap for a seamless experience.

---

## 🛠️ Installation

### Prerequisites
Make sure you have Python installed on your system.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-collection-manager.git
   cd movie-collection-manager
    ```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Set up the TMDB API:
- Get your API key from TMDB.
- Replace USE_YOUR_OWN_CODE in the code with your API key.
4. Initialize the database:
```bash
python -c "from app import db; db.create_all()"
```
5. Run the application:
```bash
python app.py
```
---
## 🧰 Built With
- **Flask** - Backend framework
- **SQLAlchemy** - Database ORM
- **Bootstrap 5** - Styling and layout
- **WTForms** - Form validation
- **TMDB API** - Movie data integration
---
## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
```bash
git checkout -b feature-name
```
3. Commit your changes:
```bash
git commit -m "Add a meaningful message"
```
4. Push to the branch:
```bash
git push origin feature-name
```
5. Open a pull request.
---
## 🌟 License
This project is licensed under the MIT License. See the LICENSE file for details.
---
## 🎯 To Do
-  Add user authentication.
- Implement sorting options.
 - Enhance UI with additional themes.
---
Enjoy managing your movie collection! 🍿
---
