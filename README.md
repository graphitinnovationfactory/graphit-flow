# GraphitFlow 🚀

**GraphitFlow** este o platformă open-source de task management dezvoltată de **Graphit Innovation Factory**. Acest proiect este dedicat programului de internship, oferind studenților oportunitatea de a lucra pe o stivă tehnologică modernă și de a contribui la un instrument real de productivitate.

## 🛠 Tehnologii Utilizate

* **Backend:** Django (Python 3.10+)
* **Frontend:** JavaScript (ES6+), Bootstrap 5, CSS3 Custom Styles
* **Bază de date:** PostgreSQL
* **Task Queue:** Celery & Redis (pentru procesări asincrone)
* **Containerizare:** Docker & Docker Compose

## 🚀 Funcționalități (MVP)

* **Dashboard Interactiv:** Vizualizarea task-urilor curente și a progresului echipei.
* **Sistem de Task-uri:** Creare, editare, ștergere și asignare de priorități.
* **Notificări în fundal:** Gestionate via Celery pentru remindere automate și raportări.
* **User Management:** Sistem complet de autentificare și roluri pentru studenți și mentori.

## 📦 Instalare și Rulare (Docker)

1.  **Clonează repository-ul:**
    ```bash
    git clone https://github.com/graphitinnovationfactory/graphit-flow.git
    cd graphit-flow
    ```

2.  **Configurează variabilele de mediu:**
    Creează un fișier `.env` pornind de la exemplul oferit:
    ```bash
    cp .env.example .env
    ```

3.  **Lansează aplicația:**
    ```bash
    docker-compose up --build
    ```

4.  **Accesează aplicația:**
    Deschide browserul la adresa [http://localhost:8000](http://localhost:8000).

## 🤝 Contribuie

Încurajăm studenții în practică să contribuie activ! Pentru a începe:
1. Caută issue-urile marcate cu `good first issue`.
2. Creează un branch nou: `git checkout -b feature/nume-task`.
3. Trimite un **Pull Request** către branch-ul `develop`.

---
© 2026 **Graphit Innovation Factory**
