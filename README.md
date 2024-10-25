# Stats Under the Stars 2024 - Hackathon
Our team composed of myself, Gianluca Procopio, Filippo Parlanti and Himel Ghosh achieved second place in the "Stats Under the Stars (SUS 7) Hackathon" an event endorsed by the Italian Statistical Society (SIS) and sponsored by Adecco and received the “Best Objective Prediction” award (€600). Stats Under the Stars (SUS) is a hackathon for Data Scientists, MSc and PhD students, where the teams have a full night to compete in the analysis of a real-world analytics problem. This year, SUS7 was organized by the University of Salento - Department of Human and Social Sciences in collaboration with Young SIS. 

## The challenge
The challenge consisted of solving a real-life problem. We were given 3 datasets: one for job vacancies, one for applicants, and one to join 5 different applicants to each job vacancy. Obviously, for each job only one candidate could be chosen while the same candidate could be chosen for multiple jobs.

Essentially, this was a classification problem that required a lot of preprocessing of the given datasets in order to obtain a final version to train our model on. We took advantages of similarities to try to figure out how similar a candidate was to a certain job position, such that for each couple Job-Candidate our model will produce a certain probability, and then for each job position we will set to 1 the candidate with the highest probability (i.e., the chosen one) and to 0 all the others.

<div align="center">
    <img src="https://github.com/bergio13/sus2024-hackathon/blob/main/prize.jpg" style="width: 50%;" alt="Prize" />
</div>

---
### Links
- Adecco SUS2024: https://www.adecco.it/news/entries/sus-2024-stats-under-the-stars
- Stats Under the Stars 2024: https://sites.google.com/view/sus2024
- y-SIS: https://youngsis.github.io

