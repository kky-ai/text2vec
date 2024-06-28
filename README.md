### text2vec
---
For emotions, we have two models now:
- english
- czech / multi-lingual

#### Example (EN):
```
:: What the hell! I hate those disgusting people.
Vector length: 38
	intent
		statement: 0.6635
		rhetorical question: 0.317
		rhetorical command: 0.0079
	emotion
		disgust: 0.7513
		anger: 0.1997
		annoyance: 0.1075
	sentiment
		neutral: 0.4117
		negative: 0.3224
		positive: 0.2659
	t: 0.3s

:: What a beautiful day!
Vector length: 38
	intent
		statement: 0.6154
		rhetorical question: 0.3656
		question: 0.0072
	emotion
		admiration: 0.9097
		joy: 0.0859
		excitement: 0.0593
	sentiment
		neutral: 0.3684
		negative: 0.3257
		positive: 0.306
	t: 0.19s
```