body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: #f5f5f5;
    color: #333;
}

header {
    background: #2c5530;
    padding: 16px;
    color: #fff;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    align-items: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin-left: 14px;
}

#destaque {
    background: linear-gradient(135deg, #2c5530, #4a7c59, #8fbc8f);
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.btn {
    display: inline-block;
    margin-top: 15px;
    padding: 12px 20px;
    background: #fff;
    color: #2c5530;
    border-radius: 6px;
    font-weight: bold;
}

section {
    padding: 60px 20px;
    background: white;
    margin-bottom: 20px;
}

h2 {
    text-align: center;
    margin-bottom: 30px;
    color: #2c5530;
}

.impacto-grid {
    display: grid;
    grid-template-columns: repeat(2,1fr);
    gap: 15px;
    text-align: center;
}

.galeria-grid {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 10px;
}

.galeria-grid img {
    width: 100%;
    border-radius: 8px;
}

form input, form textarea, form button {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
}

form button {
    background: #2c5530;
    color: white;
    border: none;
    font-weight: bold;
}

footer {
    background: #2c5530;
    color: white;
    text-align: center;
    padding: 20px;
}
