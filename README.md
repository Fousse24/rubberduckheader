
# Rubberduck Engine Header for VSCode

This extension provides the rubberduck engine header integration in VS Code.
This is very heavily based on https://github.com/kube/vscode-42header.

```bash
*********************************************************************************
*                  *#########                                                   *
*                 ##........../##           KWAK!                               *
*               *#,.......,##....#######  /                                     *
*               ##........./....##////##                                        *
*     ##          ##...........,##((#                                           *
*    #.###/        ##,..........*                                               *
*   #(.....(######(###*........,##                                              *
*  ##.............................##      File    : README                      *
*  ##.    __       __  o       __  ##                                           *
*  ##.   |_  |\\ | | __ | |\\ | |_    *#.   Created : Fousse24                    *
*   ##   |__ | \\| |__| | | \\| |__   ,#,             15/06/2022                  *
*    ##.............................##                                          *
*     /##........................*##      Updated : Fousse24                    *
*        ###/................*###.                  15/06/2022                  *
*             ##############.                                                   *
*********************************************************************************
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install 42header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "rubberduckheader.username": string,
  "rubberduckheader.email": string
}
```

## License

MIT
