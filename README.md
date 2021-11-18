# React Tic Tac Toe

# Table of contents

1. [Project Goals](#description)
2. [Technologies](#tech)
3. [System Features](#sys-features)
4. [Installation instructions](#installation)
5. [Screenshots](#screenshots)

## 1. Project description<a name="description"></a>

In this project, I build an interactive tic-tac-toe game with React.

## 2. Technologies<a name="tech"></a>

This system is provisioned to be built in JavaScript using React library which is highly flexible.

The browser will be in charge of rendering this application in its final form, HTML. Some of the logic involved in creating the web page, especially the one in charge of dealing with presentation logic is handled on the client-side.

List of frontend dependencies and version used:

-   react: v17.0.2
-   react-dom: v17.0.2
-   react-scripts: 4.0.3
-   web-vitals: v1.0.1

## 3. System Features<a name="sys-features"></a>

### Board

-   Keep the state of the grid
-   Handle Click to permute X in O on each play (and vice versa)
-   Add the player moves to the state of the grid
-   Render grid of 9 squares (child component)
-   Calculate winner
-   Check if grid is full
-   Allow to reset the game (reset state of the grid)

### Square

-   Display value from board components state (passed as props.value)

## 4. Installation instructions<a name="installation"></a>

Versions:

-   Node: 12.19.0
-   Npm: 7.6.3
-   React: 17.0.2

Download code from Github:

```shell
git clone https://github.com/antoineratat/react_jammming.git
```

Navigate to project directory.

```shell
cd react_jammming
```

Install node modules.

```shell
yarn install
```

Run the app in development mode. Open http://localhost:3000 to view it in the browser.

```shell
yarn start
```

## 5. Screenshots<a name="screenshots"></a>

![Components Screenshot](https://github.com/antoineratat/github_docs/blob/main/react_tictactoe/tictactoe.PNG?raw=true)
