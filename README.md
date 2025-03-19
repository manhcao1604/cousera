#gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

figure {
    border: 1px solid #ddd;
    padding: 5px;
    text-align: center;
}

img {
    width: 100%;
    height: auto;
}

img:focus {
    outline: 3px solid #4A90E2;
}
