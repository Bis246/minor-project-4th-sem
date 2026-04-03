#include <iostream>
#include <string>
#include <cstdlib>

using namespace std;

int main() {
    string command;

    cout << "===================================" << endl;
    cout << "      TEXT BASED PC CONTROLLER     " << endl;
    cout << "===================================" << endl;

    cout << "\nType your command: ";
    getline(cin, command);

    if (command == "note") {
        system("start notepad");
    }
    else if (command == "ch") {
        system("start chrome");
    }
    else if (command == "yt") {
        system("start https://www.youtube.com");
    }
    else if (command == "wp") {
        system("start https://web.whatsapp.com");
    }
    else if (command == "is") {
        system("start https://infyspringboard.onwingspan.com/");
    }
    else if (command == "open excel") {
        system("start excel");
    }
    else if (command == "cal") {
        system("start calc");
    }
    else if (command == "time") {
        system("time /T");
    }
    else if (command == "open html") {
        system("start index.html");
    }
    else if (command == "shutdown pc") {
        system("shutdown /s /t 10");
    }
    else if (command == "paint") {
    system("start mspaint");
    }
    else if (command == "cmd") {
    system("start cmd");
    }
    else if (command == "fm") {
    system("start explorer");
    }
    else if (command == "cp") {
        system("start control");
    }
    else if (command == "setting") {
        system("start ms-settings:");
    }
    else if (command == "tm") {
        system("start taskmgr");
    }
    else if (command == "vs") {
        system("start code");
    }
    else if (command == "sp") {
        system("start spotify");
    }
    else if (command == "tel") {
        system("start telegram");
    }
    else if (command == "insta") {
        system("start https://www.instagram.com");
    }
    else if (command == "gmail") {
        system("start https://mail.google.com");
    }
    else if (command == "restart pc") {
        system("shutdown /r /t 10");
    }
    else if (command == "google") {
        system("start https://www.google.com");
    }

    else if (command == "linkedin") {
        system("start https://www.linkedin.com");
    }
    else if (command == "github") {
        system("start https://www.github.com");
    }
    else if (command == "chatgpt") {
        system("start https://chat.openai.com");
    }
    else if (command == "download") {
        system("start shell:Downloads");
    }
    else if (command == "document") {
        system("start shell:Documents");
    }
    else if (command == "desktop") {
        system("start shell:Desktop");
    }
    else if (command == "Picture") {
        system("start shell:Pictures");
    }
    else if (command == "gc") {
        system("start https://classroom.google.com");
}
    return 0;
}
