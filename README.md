# The Chess AI


An advanced chess system built as a Streamlit app, where two AI agents compete against each other using Autogen, featuring strong move validation and comprehensive game state management.

## Features

### Multi-Agent Architecture
-White Player: An OpenAI-driven agent focused on strategic planning 
-Black Player: An OpenAI-driven opponent specializing in tactical play 
-Board Proxy: A validation component that ensures move legality and maintains the game state
### Safety & Validation
-Comprehensive move validation mechanism 
-Prevention of illegal actions during gameplay 
-Continuous monitoring of the board state in real time 
-Controlled and secure progression of the game
### Strategic Gameplay
-AI-based evaluation of board positions 
-In-depth tactical computation 
-Adaptive strategies that evolve during play 
-Full implementation of standard chess rules


### How to get Started?

1. Clone the GitHub repository

```bash
git clone https://github.com/soukingfisher/the-chess.git
cd chess.py
```
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
3. Get your OpenAI API Key

- Sign up for an [OpenAI account](https://platform.openai.com/) (or the LLM provider of your choice) and obtain your API key.

4. Run the Streamlit App
```bash
streamlit run ai_chess_agent.py
```
