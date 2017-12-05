1. Overview
    1. The idea is to create a chess program in Java
    2. Use Chef for continuous automation
    3. Use Puppet to manage infrastructure 
    4. Use Maven for dependency and builds
    5. Use JUNIT to test
    6. Write runtime scripts in Python
    7. Deploy to Raspberry Pi and AWS
2. The Chess Program 
    1. For Chess Rules see the following:
        1. https://www.chess.com/learn-how-to-play-chess
    2. Chess Piece
        1. King
        2. Queen
        3. Bishop
        4. Knight
        5. Rook
        6. Pawn
    3. Chess Piece attributes
        1. Name
        2. Color
        3. Move Pattern
        4. Value (Pawn=1. Knight=3, Bishop=3, Rook=5, Queen=9, King=Infinity)
        5. OnBoard
        6. Position on Board (Use locator designation)
        7. Other
    4. Board Layout
        1. Board Size
        2. Squares[]
            1. Color
            2. Locator (a to h, 1 to 8) Top left is a1
            3. Piece on Square
            4. Other
        3. Other
    5. Special Rules
        1. Promotion
        2. En Passant
        3. Castling 
        4. Checkmate
        5. Stalemate
    6. Strategy
        1. Control the center of the board
        2. Protect the King
        3. Use all pieces
    7. Game
        1. White player
        2. Black player
        3. Timed game
        4. Touch move
        5. Whose move is it
    8. The Java classes
        1. Chess Piece Abstract or Interface Or lambada 
