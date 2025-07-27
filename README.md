 📰 Fake News Detection: Human vs AI Intelligence:

This project explores the fundamental question:  
“Does human intelligence still outshine artificial intelligence?”

By comparing the accuracy of  AI-based Fake News Detection  with human judgment, we aimed to evaluate the reliability, strengths, and limitations of both.

📌 Objective:

	Build a system to detect fake news using a pre-trained NLP model.
	Collect human predictions on the same news articles.
	Analyze and compare the results to see who gets it right more often — humans or AI.

🧠 Tools & Technologies Used:

	Python  (Colab for development)
	Hugging Face Transformers   (pipeline for text classification)
	Pre-trained Model:  (vikram71198/distilroberta-base-finetuned-fake-news-detection)
	Google Forms   (for collecting human predictions)
	Microsoft Excel (for organizing survey data)
	Excel Charts (for visual comparison and analysis)

 📁 Project Structure:

	notebooks/ – Colab notebooks with AI code
	forms/ – Google Form links or structure for human evaluation
	data/ – Collected news headlines, human responses, and AI predictions
	visuals/ – Charts comparing AI and human accuracy
	README.md – Project overview (this file)

🧪 Methodology:

1. News Collection:
	Gathered 12 news items (6 fake, 6 real).
	Included a mix of believable fake stories and surprising real ones.

2. AI Prediction:
	Used Hugging Face pipeline with the model (vikram71198/distilroberta-base-finetuned-fake-news-detection).
	Collected model predictions and confidence scores.

3. Human Judgment:
	Created Google Forms with the same 12 news headlines.
	Asked participants to label each as "Fake" or "Real".

4. Comparison:
	Combined results into Excel.
	Calculated accuracy for both AI and human groups.
	Created visualizations showing comparative performance.

 📊 Key Insights:

	Model Accuracy: ~83% (correctly predicted 10 out of 12)
	Human Accuracy:  Varied (average around 72% depending on participant)
	Observation:  While AI performed strongly, humans showed deeper context awareness in certain nuanced stories.
 ✅ Outcome:

	AI showed  speed and consistency.
	Humans showed  intuition,  contextual understanding, and  critical thinking.
	Both have their strengths — combining them may lead to optimal results.

 🔍 Challenges Faced:

	Finding  balanced and believable  news items.
	Ensuring  unbiased human responses  (avoiding Googling).
	Dealing with  model limitations — some models labeled all headlines as fake.
	Cleaning and comparing data from different sources.

🚀 What We Learned:

	How to use pre-trained NLP models from Hugging Face.
	How to collect and analyze survey data.
	How to draw meaningful insights by  comparing AI and human reasoning.
	The value of both perspectives  in real-world decision-making.

💡 Future Work:

	Train a custom model on local language or niche domains.
	Involve more diverse human participants for a broader comparison.
	Integrate fact-check APIs for real-time validation.

🙌 Team:

•	Asima Shafiq
•	Areeba Ashraf

Link:


Here is the link of demo Video . You can check :)

https://youtu.be/IvCs_vglpXU?si=s9hMi_qkd5mG4AkO


📬 Get Involved:

Interested in contributing, testing, or extending this project?  
Feel free to fork, star ⭐, or open an issue.
