```
import socket
import re
from time import sleep

def getbestmove(board):
    #print(board)
    if board == "012345678" or board == "012345678012345678"or board == "012345678012345" or board == "012345678":#FirstMove
        return "0"
    elif board == "X☺2345678" or board == "X1☺345678" or board == "X1234☺678" or board == "X123456☺8" or board == "X1234567☺":#secondmoves
        return "6"
    elif board == "X12☺45678" or board == "X12345☺78":
        return "2"
    elif board == "X123☺5678" or board == "X☺X☺☺XX☺8":#only possible tie line
        return "8"
    if board[6]=="X":#15
        if board[3]=="3": return "3"
        if board[3]=="☺" and board[2]=="2" and board[5]=="5" and board[1]!="☺": return "2"
        if board[8]=="X" and board[4]=="4": return "4"
        if board[3]=="☺" and board[7]=="☺" and board[2]=="2": return "2"
        if board[6]=="X" and board[2]=="X" and board[4]=="4": return "4"
        if board[2]=="X" and board[1]=="1": return "1" 
        if board[3]=="☺" and board[1]=="☺" and board[8]=="8": return "8"
        if board[6]=="X" and board[8]=="X" and board[7]=="7": return "7" 
        if board[3]=="☺" and board[2]=="2" and board[5]=="☺" and board[4]=="4": return "4"
        if board[3]=="☺" and board[2]=="X" and board[1]=="1": return "1"
        if board[3]=="☺" and board[2]=="X" and board[4]=="4": return "4"
        if board[3]=="☺" and board[2]=="☺" and board[8]=="8": return "8"
        if board[3]=="☺" and board[2]=="☺" and board[8]=="X" and board[4]=="4": return "4"
        if board[3]=="☺" and board[2]=="☺" and board[8]=="X" and board[7]=="7": return "7"
    if board[1]==board[4] and board[4]=="4": return "4"
    if board[2]=="X":
        if board[1]=="1": return "1"
        if board[1]=="☺" and board[6]=="6" and board[3]!="☺": return "6"
        if board[1]=="☺" and board[8]=="8" and board[3]=="☺": return "8"
        if board[8]=="X" and board[4]=="4": return "4"
        if board[8]=="X" and board[2]=="X" and board[5]=="5": return "5"
        if board[1]=="☺" and board[6]=="X" and board[3]=="3": return "3"
        if board[1]=="☺" and board[6]=="X" and board[4]=="4": return "4"
        if board[1]=="☺" and board[6]=="☺" and board[8]=="8": return "8"
        if board[1]=="☺" and board[6]=="☺" and board[8]=="X" and board[4]=="4": return "4"
        if board[1]=="☺" and board[6]=="☺" and board[8]=="X" and board[5]=="5": return "5"
    if board[4]=="☺":#dontlose
        if board[3]=="☺" and board[5]=="5": return "5"
        if board[5]=="☺" and board[3]=="3": return "3"
        if board[1]=="☺" and board[7]=="7": return "7"
        if board[7]=="☺" and board[1]=="1": return "1"
        if board[6]=="☺" and board[2]=="2": return "2"
        if board[6]=="☺" and board[2]=="2": return "2"
        if board[2]=="☺" and board[6]=="6": return "6"
    if board[4]=="X":
        if board[8]=="8": return "8"
        if board[6]=="X" and board[2]=="2": return "2"
    
    else:
        number = (len(str(re.sub('[^0-9]+', '', board))))
        if number==1: return str(re.sub('[^0-9]+', '', board))
        else: return "9"
        print("not there yet This is left: "+ str(re.sub('[^0-9]+', '', board)))

def getboard():
    s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
    s.connect(('192.168.37.1', 9090))
    while True:
        data = s.recv(1024)
        sleep(.005)
        if "flag" in data.decode("utf-8"):
            print (data.decode("utf-8"))
            break
        sendme=translateboard(data.decode("utf-8"))#57
        sleep(.001)
        #print("Sendme + " + sendme)
        sleep(.001)
        #print("Sending " + sendme)
        s.send(bytes(sendme, "utf-8"))
        sleep(.001)



def translateboard(rawboard):
    #print(rawboard)
    rawboard = re.sub('[^X0-9☺t]+', '', rawboard)
    #print(rawboard)
    if rawboard == "": rawboard = "ttttttttt"
    #print("rawboard + " + getbestmove(rawboard))
    return(getbestmove(rawboard))#75

def sendmove():
    print("hello")


getboard()

```