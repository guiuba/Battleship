# Battleship
This is my solution to JetBrains Academy Battleship project stage 5/5

Example
The greater-than symbol followed by a space (> ) represents the user input. Notice that it's not part of the input.

Player 1, place your ships on the game field

  1 2 3 4 5 6 7 8 9 10
  
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~


Enter the coordinates of the Aircraft Carrier (5 cells):

> F3 F7

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Battleship (4 cells):

> A1 D1

  1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ ~ ~
C O ~ ~ ~ ~ ~ ~ ~ ~ ~
D O ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Submarine (3 cells):

> J7 J10

Error! Wrong length of the Submarine! Try again:

> J10 J8

  1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ ~ ~
C O ~ ~ ~ ~ ~ ~ ~ ~ ~
D O ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ O O O

Enter the coordinates of the Cruiser (3 cells):

> B9 D8

Error! Wrong ship location! Try again:

> B9 D9

  1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ O O O

Enter the coordinates of the Destroyer (2 cells):

> E6 D6

Error! You placed it too close to another one. Try again:

> I2 J2

  1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ O ~ ~ ~ ~ ~ ~ ~ ~
J ~ O ~ ~ ~ ~ ~ O O O

Press Enter and pass the move to another player
...
Player 2, place your ships to the game field

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Aircraft Carrier (5 cells):

> H2 H6

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ O O O O O ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Battleship (4 cells):

> F3 F6

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ O O O O O ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Submarine (3 cells):

> H8 F8

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

...

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ O ~ ~
D ~ ~ ~ O O O ~ O ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Press Enter and pass the move to another player
...

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
---------------------
  1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ O ~ ~ ~ ~ ~ ~ ~ ~
J ~ O ~ ~ ~ ~ ~ O O O

Player 1, it's your turn:

> I3

You missed!
Press Enter and pass the move to another player
...

  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
---------------------
  1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ O ~ ~
D ~ ~ ~ O O O ~ O ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ M ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Player 2, it's your turn:

> A1

You hit a ship!
Press Enter and pass the move to another player
-----------------------------------------------

public class Player2 extends BaseClass {

    public Player2(String name) {
        super(name);
    }

}

import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public abstract class BaseClass {
    protected String name;
    protected String[][] hiddenGameField = new String[11][11];
    protected String[][] gameField = new String[11][11];

    protected List<List<String>> shipList = new ArrayList<>();
    static Scanner scan = new Scanner(System.in);
    static int rowInit;
    static int colInit;
    static int rowFin;
    static int colFin;
    static boolean isHorizontal = false;
    static boolean gameIsOver = false;


    public BaseClass(String name) {
        this.name = name;
    }

    boolean updateMove(String move) {
        List<List<String>> removeShip = new ArrayList<>();

        for (List<String> ship : shipList) {

            ship.removeIf(str -> str.contains(move));

            if (ship.isEmpty() && !shipList.isEmpty()) {
                removeShip.add(ship);
                shipList.removeAll(removeShip);
                if (shipList.isEmpty()) {
                    System.out.println("You sank the last ship. You won. Congratulations!");
                    gameIsOver = true;
                    return true;
                }
                System.out.println("You sank a ship! Specify a new target:");
                return false;
            }
        }

        System.out.println("You hit a ship!");
        return false;
    }

    boolean runGame() {

        String shot = scan.next().toUpperCase();
        int row;
        int col;
        row = Integer.parseInt(String.valueOf(shot.charAt(0) - 64));
        col = Integer.parseInt(shot.substring(1));

        if ("~".equals(gameField[row][col])) {
            gameField[row][col] = "M";
            hiddenGameField[row][col] = "M";
            System.out.println("You missed!");
        } else if ("O".equals(gameField[row][col]) ||
                "X".equals(gameField[row][col])) {
            gameField[row][col] = "X";
            hiddenGameField[row][col] = "X";

            String move = row + " " + col;
            return updateMove(move);
        }
        return false;
    }

    boolean checkMove(String coord1, String coord2, ShipType battleShip) {
        rowInit = Integer.parseInt(String.valueOf(coord1.charAt(0) - 64));
        colInit = Integer.parseInt(coord1.substring(1));
        rowFin = Integer.parseInt(String.valueOf(coord2.charAt(0) - 64));
        colFin = Integer.parseInt(coord2.substring(1));
        int shipLength;
        int aux;
        boolean closeToAnother = false;
        if (colFin < colInit) {
            aux = colInit;
            colInit = colFin;
            colFin = aux;
            aux = rowInit;
            rowInit = rowFin;
            rowFin = aux;
        }
        if (rowFin < rowInit) {
            aux = rowInit;
            rowInit = rowFin;
            rowFin = aux;
            aux = colInit;
            colInit = colFin;
            colFin = aux;
        }
        if (rowInit == rowFin) {
            shipLength = colFin - colInit + 1;
            isHorizontal = true;
        } else if (colInit == colFin) {
            shipLength = rowFin - rowInit + 1;
        } else {
            System.out.println("Error! Wrong ship location! Try again:");
            return false;
        }
        // checks if there is ship has a different size
        if (shipLength != battleShip.getSize()) {
            System.out.printf("Error! Wrong length of the %s! Try again:\n", battleShip.getType());
            return false;
        }

        if (isHorizontal) {
            if (colInit > 1) {
                if ("O".equals(gameField[rowInit][colInit - 1])) {
                    closeToAnother = true;
                }
            }
            if (colFin < 10) {
                if ("O".equals(gameField[rowFin][colFin + 1])) {
                    closeToAnother = true;
                }
            }
        } else {
            if (rowInit > 1) {
                if ("O".equals(gameField[rowInit - 1][colInit])) {
                    closeToAnother = true;
                }
            }
            if (rowFin < 10) {
                if ("O".equals(gameField[rowFin + 1][colFin])) {
                    closeToAnother = true;
                }
            }
        }
        if (closeToAnother) {
            System.out.println("Error! You placed it too close to another one. Try again:");
            return false;
        }

        return true;
    }

    void placeFleet() {

        boolean isValid;
        for (ShipType s : ShipType.values()) {
            System.out.printf("Enter the coordinates of the %s (%d cells):\n", s.getType(), s.getSize());

            List<String> shipCoordinates = new ArrayList<>();

            isValid = checkMove(scan.next().toUpperCase(), scan.next().toUpperCase(), s);
            while (!isValid) {
                isValid = checkMove(scan.next().toUpperCase(), scan.next().toUpperCase(), s);
            }
            if (isHorizontal) {
                for (int i = colInit; i <= colFin; i++) {
                    gameField[rowInit][i] = "O";
                    shipCoordinates.add(rowInit + " " + i);
                }
                isHorizontal = false;
            } else {
                for (int j = rowInit; j <= rowFin; j++) {
                    gameField[j][colInit] = "O";
                    shipCoordinates.add(j + " " + colInit);
                }
            }

            shipList.add(shipCoordinates);
            printGameField(gameField);
        }
    }

    String[][] gameFieldSetUp(String[][] passedGameField) {
        for (int row = 0; row < passedGameField.length; row++) {
            for (int col = 0; col < passedGameField.length; col++) {
                passedGameField[row][col] = "~";
                passedGameField[0][0] = "  ";
                if (row == 0 && col > 0) {
                    passedGameField[0][col] = String.valueOf(col);
                }
                if (row > 0 && col == 0) {
                    passedGameField[row][0] = (char) (row + 64) + " ";
                }
            }
        }
        return passedGameField;
    }

    void printGameField(String[][] passedGameField) {
        System.out.println();
        for (String[] gameFieldRow : passedGameField) {
            for (String gameFieldRowElem : gameFieldRow) {
                System.out.print(gameFieldRowElem + " ");
            }
            System.out.println();
        }
        System.out.println();
    }


}
src/battleship/ShipType.java
package battleship;

public enum ShipType {
    AIRCRAFTCARRIER("Aircraft Carrier", 5), BATTLESHIP("Battleship", 4),
    SUBMARINE("Submarine", 3), CRUISER("Cruiser", 3),
    DESTROYER("Destroyer", 2);

    private final String type;
    private final int size;


    ShipType(String type, int size) {
        this.type = type;
        this.size = size;

    }

    public String getType() {
        return type;
    }

    public int getSize() {
        return size;
    }

}

import java.io.IOException;
import java.util.Arrays;
import java.util.List;

public class Main {
    static List<BaseClass> players = Arrays.asList(new Player1("Player 1"), new Player2("Player 2"));
    static BaseClass currentPlayer = players.get(0);

    public static void main(String[] args) {
        placeFleet();
        currentPlayer = players.get(1 - players.indexOf(currentPlayer));
        while (true) {
            displayGameFields();
            if (currentPlayer.runGame()) {
                System.exit(0);
            }
            changePlayer();
        }
    }

    static void displayGameFields() {
        currentPlayer.printGameField(currentPlayer.hiddenGameField);
        System.out.println("-----------");
        currentPlayer = players.get(1 - players.indexOf(currentPlayer));
        currentPlayer.printGameField(currentPlayer.gameField);

        System.out.printf("%s, it's your turn:\n", currentPlayer.name);
        currentPlayer = players.get(1 - players.indexOf(currentPlayer));
    }

    static void placeFleet() {
        int times = 2;
        while (times-- > 0) {
            currentPlayer.gameFieldSetUp(currentPlayer.hiddenGameField);
            System.out.printf("%s, place your ships on the game field\n", currentPlayer.name);
            currentPlayer.printGameField(currentPlayer.gameFieldSetUp(currentPlayer.gameField));
            currentPlayer.placeFleet();
            changePlayer();
        }
    }

    static void changePlayer() {
        System.out.println("Press Enter and pass the move to another player");
        try {
            System.in.read();
            currentPlayer = players.get(1 - players.indexOf(currentPlayer));
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}


public class Player1 extends BaseClass {

    public Player1(String name) {
        super(name);
    }

}
