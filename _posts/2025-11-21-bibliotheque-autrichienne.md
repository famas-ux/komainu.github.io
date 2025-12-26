<style>
/* Conteneur principal */
.library-container {
    max-width: 1000px;
    margin: auto;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
    color: #1c1c1e; /* texte sombre */
    background-color: #ffffff; /* fond blanc */
    padding: 20px;
}

/* Titres */
.library-container h1 {
    text-align: center;
    font-size: 32px;
    color: #007f3f; /* vert sombre */
    margin-bottom: 15px;
}

.library-container h2 {
    font-size: 24px;
    color: #007f3f; /* vert sombre */
    margin-top: 30px;
    margin-bottom: 10px;
    border-bottom: 2px solid #007f3f;
    padding-bottom: 5px;
}

/* Listes uniformisées avec "cartes" simples */
.library-container ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.library-container li {
    background-color: #f9f9f9; /* carte claire */
    border: 1px solid #ff8000; /* orange */
    border-radius: 6px;
    padding: 12px 15px;
    flex: 1 1 calc(33% - 10px);
    box-sizing: border-box;
    min-width: 250px;
    transition: transform 0.2s, box-shadow 0.2s;
}

.library-container li:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 15px rgba(255,128,0,0.4);
}

.library-container a {
    text-decoration: none;
    color: #ff8000; /* liens orange */
    font-weight: bold;
}

.library-container a:hover {
    text-decoration: underline;
}

/* Responsive pour petits écrans */
@media (max-width: 768px) {
    .library-container li {
        flex: 1 1 calc(50% - 10px);
    }
}

@media (max-width: 480px) {
    .library-container li {
        flex: 1 1 100%;
    }
}
</style>
