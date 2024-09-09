Acest proiect este o aplicație web simplă creată cu React, care permite utilizatorilor să caute filme folosind API-ul OMDB și să afișeze rezultatele.

### Rezumat:

- **Componenta principală (`App`)**:

  - Gestionează stările pentru lista de filme (`movies`) și termenul de căutare (`searchTerm`).
  - Funcția `searchMovies` caută filme folosind API-ul OMDB și actualizează lista de filme.
  - La montarea aplicației, se efectuează o căutare inițială pentru "Spiderman".
  - Interfața include un câmp de căutare și afișează filmele sau un mesaj de eroare.

- **Componenta `MovieCard`**:

  - Afișează detalii despre fiecare film, inclusiv posterul, titlul, anul și tipul filmului.

- **Stilizare (`App.css`)**:
  - Definește stilurile aplicației, utilizând Flexbox pentru layout și efecte vizuale pentru interacțiuni.

Inspiration: https://gist.github.com/adrianhajdin/997a8cdf94234e889fa47be89a4759f1?permalink_comment_id=4454192

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
