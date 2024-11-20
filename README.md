# Stratego

## Game Explanation

**Basic Concept:**
Stratego is a two-player strategy board game where each player controls an army and tries to capture the opponent's flag while protecting their own.

**Setup:**
1. Each player has 8 pieces in this version (simplified from traditional Stratego which has 40 pieces)
2. Pieces are placed in the first two rows for Player X (top) and last two rows for Player O (bottom)

**Pieces (from highest to lowest rank):**
- G (General) - Highest rank
- M (Marshal)
- S (Spy) - Special piece: can defeat the Marshal if it attacks first
- s (Scout) - Can move multiple spaces in a straight line
- B (Bomb) - Immovable piece that defeats any piece that attacks it (except Scout)
- F (Flag) - The objective to capture

**Movement Rules:**
1. Pieces move one square at a time (except Scout)
2. Scout (s) can move any number of empty squares in a straight line
3. Bombs (B) and Flags (F) cannot move
4. Pieces can move horizontally or vertically (not diagonally)

**Combat Rules:**
1. When a piece attacks another piece:
   - Higher rank captures lower rank
   - Equal ranks both get removed
   - Special cases:
     - Spy (S) defeats Marshal (M) if Spy attacks first
     - Bomb (B) defeats any piece that attacks it (except Scout)
     - Scout (s) can defuse Bombs

**Winning Conditions:**
1. Capture the opponent's Flag
2. Opponent cannot make any legal moves
3. All opponent's movable pieces are captured