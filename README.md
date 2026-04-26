## README

This notebook provides a comprehensive set of practical problems in probability and statistics, solved using Python. It demonstrates various probabilistic concepts and their applications in real-world scenarios, such as system reliability analysis, quality control, and marketing analytics.

### Table of Contents

1.  [Task 1. System Log Error Analytics](#Task-1.-System-Log-Error-Analytics)
2.  [Task 2. Battery Quality Control](#Task-2.-Battery-Quality-Control)
3.  [Task 3. Distributed System Reliability](#Task-3.-Distributed-System-Reliability)
4.  [Task 4. Traffic Source Identification (Bayes' Theorem)](#Task-4.-Traffic-Source-Identification-(Bayes'-Theorem))

### Task 1. System Log Error Analytics

This section analyzes system monitoring logs to calculate probabilities related to database (DB) and network (NET) errors. It covers:

*   Probability of a DB error ($P(A)$)
*   Probability of a DB or NET error ($P(A \cup B)$)
*   Probability of a DB error but not a NET error ($P(A \setminus B)$)
*   A Venn diagram visualization for error distribution.

### Task 2. Battery Quality Control

This section addresses a quality control problem involving selecting batteries from a warehouse. It calculates probabilities for selecting good and defective batteries using both combinatorial methods and the multiplication rule. Key calculations include:

*   Probability that all 3 selected batteries are good.
*   Probability that exactly 2 selected batteries are good.
*   Probability that exactly 1 selected battery is good.
*   A bar chart visualization of these probabilities.

### Task 3. Distributed System Reliability

This section focuses on the reliability of a distributed system with four independent nodes, each having a specific failure probability. It determines:

*   Probability that all 4 nodes are working (continuous operation).
*   Probability that at least one node fails.
*   Probability that exactly two nodes fail.
*   A bar chart visualization for system reliability.

### Task 4. Traffic Source Identification (Bayes' Theorem)

This section applies Bayes' Theorem to analyze traffic sources for an online store. It calculates:

*   The total probability of a purchase.
*   The posterior probability that a customer came from a specific source (Email) given a purchase.
*   A programmatic implementation for calculating posterior probabilities for all sources.
*   A comparison visualization showing prior traffic share versus posterior contribution to sales.

### Usage

To use this notebook, simply open it in a Python environment (like Google Colab or Jupyter) and run the cells sequentially. The code is written in Python 3 and uses standard libraries such as `math`, `itertools`, `matplotlib.pyplot`, `numpy`, and `matplotlib_venn`.

### Contributing

Feel free to fork this repository, suggest improvements, or add more examples of probability and statistics problems. Any contributions are welcome!
