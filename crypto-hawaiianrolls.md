`
with open("rolls.dat", "rb") as f:

    answer=""

    byte1=b'0'

    while (byte := f.read(1)):

        # Do stuff with byte.

        answer += chr(ord(byte) ^ ord(byte1))

        byte1=byte

print(answer)
`