Chess Engine (Python, from scratch)

A chess engine built without external chess libraries (no `python-chess`) — 
board representation, piece movement rules, and move validation are all 
implemented directly.



 Status
🚧 In progress — board representation and piece placement are working. 
Move validation and an AI opponent are next.

Structure
- board.py — board representation and piece setup
- pieces.py — movement rules per piece type (in progress)
- game.py — turn order, check/checkmate detection (planned)
- ai.py — minimax-based opponent (planned)

Run it
bash
python board.py
