class Sudhagar:
    def __init__(self):
        self.name = "Sudhagar R"
        self.location = "Madurai, Tamil Nadu, India"
        self.degree = "M.Sc. Data Science @ The American College (2024 - 2026)"
        self.role = "Aspiring Data Analyst"

        self.stack = {
            "languages": ["Python", "SQL", "JavaScript", "HTML", "CSS"],
            "data_tools": ["Pandas", "NumPy", "Matplotlib", "Seaborn", "Excel"],
            "ml_dl": ["Scikit-learn", "CNN-LSTM", "Flask"],
            "cloud_devops": ["AWS Fundamentals"],
            "networking": ["Hardware & Networking", "CCNA", "CCNP"],
        }

        self.currently_learning = [
            "Advanced Machine Learning",
            "Cloud Data Pipelines (AWS)",
            "Cyber Security & Ethical Hacking",
        ]

        self.fun_fact = "Went from a Diploma in Fashion Designing to Data Science 🎨➡️📊"

    def motto(self):
        return "Turn raw data into actionable insights, one dataset at a time."


me = Sudhagar()
print(me.motto())
