# Recommendation Engines

In real life one decides to buy an item based on their own taste, suggestions from their friends and family and their own experience, but nowadays the digital world has grown into something that goes beyond asking around to buy something, simply because everything is now faster and more achievable over the digital world, and the buying experience (this can be anything, from buying plane tickets to a vacation, buying a shower gel to hiring a tutoring service etc.) slowly changing, evolving into a more digitized and personal experience rather than a social one.

In this digital age the recommendation systems seem to have gained an important place for themselves. In fact, they are the ones to create the real-time, personalized, current and present experience for the users. Recommendation systems use huge chunks of data to analyze to give the most accurate suggestions for the users. They merely facilitate the choosing process, by narrowing down the options for the user, in which they are predicted to be interested.

In mathematical terms;

If $U$ denotes users, $I$ denotes items then $F$ denotes utility function and computes the usefulness of item $I$ to user $U$, given by:

$$ F: U \times I \to [0, \infty)  $$

For each user $u$, we want to choose the item $i$ that maximizes the objective function: for a fixed user $u \in U$,

$$ R(u) = argmax_{i \in I} F(u,i)$$

Where $R$ denotes recommended items.