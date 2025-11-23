# Python-project
This is me VITyarthi project
# Mood-Based Movie & Song Suggestion System
# Introduction to Problem Solving Project

print("=== Mood-Based Movie & Song Recommendation System ===\n")

mood = input("How are you feeling today? ").lower()

print("\n--- Recommendations for you ---")

if mood == "happy":
    print("\nMovies:")
    print("- Zindagi Na Milegi Dobara")
    print("- Yeh Jawaani Hai Deewani")
    print("- 3 Idiots")

    print("\nSongs:")
    print("- Ilahi")
    print("- Gallan Goodiyan")
    print("- Phir Se Ud Chala")

elif mood == "sad":
    print("\nMovies:")
    print("- Tamasha")
    print("- Dear Zindagi")
    print("- Barfi")

    print("\nSongs:")
    print("- Channa Mereya")
    print("- Agar Tum Saath Ho")
    print("- Judaai")

elif mood == "stressed":
    print("\nMovies:")
    print("- The Pursuit of Happyness")
    print("- Life of Pi")
    print("- Wake Up Sid")

    print("\nSongs:")
    print("- Night Changes")
    print("- Kesariya (LoFi)")
    print("- Raabta (Acoustic)")

elif mood == "bored":
    print("\nMovies:")
    print("- Bhool Bhulaiyaa 2")
    print("- Dhol")
    print("- Fukrey")

    print("\nSongs:")
    print("- Nacho Nacho")
    print("- Kala Chashma")
    print("- Coca Cola")

elif mood == "romantic":
    print("\nMovies:")
    print("- Jab We Met")
    print("- Sita Ramam")
    print("- Ae Dil Hai Mushkil")

    print("\nSongs:")
    print("- Raatan Lambiyan")
    print("- Tum Hi Ho")
    print("- Perfect (Ed Sheeran)")

elif mood == "angry":
    print("\nMovies:")
    print("- Warrior")
    print("- Chak De India")
    print("- Bhaag Milkha Bhaag")

    print("\nSongs:")
    print("- Believer")
    print("- Zinda")
    print("- Lose Yourself")

else:
    print("\nSorry, I don't recognize this mood.")
    print("Here are general suggestions:")

    print("\nMovies:")
    print("- The Social Network")
    print("- Taare Zameen Par")
    print("- Dangal")

    print("\nSongs:")
    print("- On My Way")
    print("- Aaj Kal Zindagi")
    print("- Apna Time Aayega")
Give me README file
ChatGPT said:
Here is a clean, polished README.md file for your Mood-Based Movie & Song Recommendation System:

🎭 Mood-Based Movie & Song Recommendation System
A simple and interactive Python program that recommends movies and songs based on the user’s current mood. This project is designed for beginners in programming and problem-solving.

📌 Project Overview
This project asks the user how they are feeling and provides a list of movies and songs tailored to that mood.
It uses basic conditional statements (if-elif-else) and user input handling in Python.

🧠 How It Works
The program starts by displaying a welcome message.

It asks the user: "How are you feeling today?"

Based on the mood entered, it shows curated movie and song recommendations.

If the mood is not recognized, it displays general suggestions.

🎬 Supported Moods
The program recognizes the following moods:

happy

sad

stressed

bored

romantic

angry

If the user enters anything else, a default list is shown.

💻 Code Explanation
The project uses:

input() – to receive user mood

.lower() – to handle case-insensitive input

if-elif-else – to provide correct recommendations

print() – to display movie and song lists

This makes the project beginner-friendly and perfect for understanding decision-making in Python.

▶️ How to Run
Install Python (if not installed)

Save the script as:

mood_recommendation.py
Run the script in the terminal or any Python IDE:

python mood_recommendation.py
Enter your mood when prompted.

📄 Sample Output
=== Mood-Based Movie & Song Recommendation System ===

How are you feeling today? happy

--- Recommendations for you ---

Movies:
- Zindagi Na Milegi Dobara
- Yeh Jawaani Hai Deewani
- 3 Idiots

Songs:
- Ilahi
- Gallan Goodiyan
- Phir Se Ud Chala
🚀 Future Enhancements (Optional)
You can improve this project by adding:

GUI using Tkinter or PyQt

Randomized recommendations

A larger movie & song database

Multiple mood inputs

API integration (Spotify, IMDb)

📝 Author
This project was created as part of an Introduction to Problem Solving course to practice basic Python logic and user interaction.
