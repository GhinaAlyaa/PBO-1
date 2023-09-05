body {
    font-family: monospace, cambria;
    margin: 0;
    padding: 0;
    background-color: #e3caaf;
}

header {
    background-color: #946038;
    color: #fff;
    text-align: center;
    padding: 5px;
}

main {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    display: flex; 
    flex-wrap: wrap; 
    justify-content: space-between; 
}

.profile, .ceritapendek {
    flex-basis: calc(45% - 10px); 
    text-align: center;
    margin-bottom: 20px;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.ceritapendek {
    flex-basis: calc(55% - 80px);
    text-align: center;
    margin-bottom: 20px;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.profile img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 3px;
}

.ceritapendek img {
    width: 200px;
    height: 100px;
    border-radius: 10%;
    object-fit: cover;
    margin-bottom: 5px;
    justify-content: center;
}

.video {
    text-align: center;
    margin-bottom: 20px;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    flex-basis: 100%; 
}

input, textarea {
    width: 100%;
    padding: 5px;
    margin-bottom: 10px;
}

button {
    padding: 10px;
    background-color: #946038;
    color: #fff;
    border: none;
    cursor: pointer;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
