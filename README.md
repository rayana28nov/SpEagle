# SpEagle
Collective Opinion Spam Detection: Bridging Review Network and Metadata

Online reviews capture the testimonials of “real” people and help shape the decisions of other consumers. Due to the financial gains associated with positive reviews, however, opinion spam has become a widespread problem, with often paid spam reviewers writing fake reviews to unjustly promote or demote certain products (or businesses). Current approaches have successfully but separately utilized linguistic clues associated with deception, behavioral footprints, or relational ties between agents in a review system, to unearth suspicious reviews, users, or user groups.

In this work, we propose a new holistic approach called SpEagle that utilizes clues from all of metadata (text, timestamp, rating) as well as relational data (network), and harness them collectively under a unified framework to spot suspicious users and reviews, as well as targeted products of spam. Moreover, our method can efficiently and seamlessly integrate semi-supervision, i.e., a (small) set of labels if available, without requiring any training or changes in its underlying algorithm. We demonstrate the effectiveness and scalability of SpEagle on three real-world review datasets from Yelp.com with filtered (spam) and recommended (nonspam) reviews, where it significantly outperforms several baselines and state-of-the-art methods. To the best of our knowledge, this is the largest scale quantitative evaluation performed to date for the opinion spam problem.

http://shebuti.com/collective-opinion-spam-detection/
