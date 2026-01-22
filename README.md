# Hidden Markov Model (HMM) for DNA Sequence Analysis

## Project Overview
This project implements a Hidden Markov Model (HMM) to analyze DNA sequences. The HMM is trained using the Baum-Welch algorithm to learn transition and emission probabilities. The model is then used to decode the most likely hidden state sequence for a given DNA sequence using the Viterbi algorithm.

## Dataset Description
* The dataset contains DNA sequences of nucleotides: A, C, G, T.
* Sequences are encoded as integers: A=0, C=1, G=2, T=3.

## Project Structure
* Data Preparation: Loading and encoding DNA sequences.
* HMM Implementation: Forward, Backward, Baum-Welch, and Viterbi algorithms.
* Training: Baum-Welch algorithm to learn HMM parameters.
* Decoding: Viterbi algorithm to find the most likely hidden state sequence.

## Key Findings
* The HMM successfully learns transition and emission probabilities from the DNA sequences.
* The Viterbi algorithm effectively decodes the most likely hidden state sequence.

## Technologies Used
* Python
* NumPy
* Pandas

## Future Work
* Improve model accuracy by incorporating additional features or using more advanced algorithms.
* Apply the HMM to other biological sequence analysis tasks.
