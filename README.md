# Sarcasm_Detector
A neural network for sarcasm detection I trained on the reddit sarcasm database

It achieved an accuracy of roughly 57%, which isn't very impressive. The best academic results I could find were in the 60s, but Yahoo claims to have a proprietary model that can detect sarcasm with 80% accuracy.

I was hopiing that with the release of the new, larger reddit dataset, the academic result could be improved on but I haven't had much success with it so far. I also tried adding sentiment analysis information based on a theory I read that sarcastic sentences tend to have  very positive and very negative sentiments close together (i.e. "First I was fired, then my girlfriend dumped me -- what a great day!")

I suspect that incorporating context (the preceding comments) would be a better strategy for text-based sarcasm detection. Also incorporating audio if your problem permits it would, I believe, make it a much simpler problem allowing for accuracy rates over 80%.
