# This is a small collection of quizzes related to coding

The can be runned using the BreatheCode Platform

To Create a new quiz just create a JSON file with the following syntax:

```json
{
    "info": {
        "slug":    "new",
        "name":    "Example Quiz",
        "status":    "draft",
        "main":    "Self-assessment",
        "results": "Congratulations! Now you know Kung Fu!",
        "badges": [
            { "slug": "css_master", "points": 23 }
        ]
    },
    "questions": [
        {
            "q": "Which of the following is correct ?",
            "a": [
                {"option": "Wulululu.",      "correct": false},
                {"option": "Welelelele",     "correct": false},
                {"option": "PEPEPE",      "correct": false},
                {"option": "PIPIPIPI",      "correct": true}
            ]
        }
    ]
}
```

### 💾 Save the file as a JSON file, for example: `html.json`

### If your quiz is in 🇪🇸 Spanish add the language code into your file name like this: `html.es.json` instead of `html.json`
