# F-O-O-K-G-H-I-D-R-A

# https://drive.google.com/file/d/18O2b8RA133Lvccl4kmdrY3AR2SyFZyg1/view?usp=sharing


# python cannot be reverse engineered period


# Made in India , West Bengal


# By a former 6 pointer of VIT VELLORE , India


# Atmanirbhar BHARAT

# Copyrighted and protected by the Berne Convention

#  https://www.linkedin.com/in/neelanjanmanna/


from Crypto import Random
from Crypto.Cipher import AES
import hashlib
import c
import b
import random
import easygui
import os
import pyotp
import time

class Decryptor:
    
    def _init_(self, key, file_name):
        self.key = hashlib.sha256(key.encode('utf-8')).digest()
        self.file_name = file_name

    
    def pad(self, s):
        return s + b'\x00' * (AES.block_size - len(s) % AES.block_size)

    
    def decrypt(self, ciphertext, key):
        iv = ciphertext[:AES.block_size]
        cipher = AES.new(key, AES.MODE_CBC, iv)
        plaintext = cipher.decrypt(ciphertext[AES.block_size:])
        return plaintext.rstrip(b'\x00')

    
    def decrypt_file(self):
        dec = self.decrypt(self.file_name, self.key)
        return dec



class BruteForce:
    
    def _init_(self, encrypted_codes):
        self.encrypted_codes = encrypted_codes
        self.password = 0

    
    def start(self):
Unsupported opcode: JUMP_IF_NOT_EXC_MATCH
        status = True
    # WARNING: Decompyle incomplete


# encrypted_codes = b'(\xce\xe18\x9fzD\xc4!9l\xfa\xe1#\xa8c\xc3\xf2\xe5]=\x90o\xd46%\x8d\x88\x1cQ\x85R\xed\x81\xd3\xac\xd8\xd2\x8d\xf9\xec\x9cr\x07Q\x11w\xd1\x9a\x12\xb5\xe2d\xae\x9dm\x18\xcb;\x90\x94\xa9\xcf\xe4N\xd0s\x16\xfb\x8f\x7f\xa3\x18\rV\xf6\xce$#\xca\x81\x97\xc1;\x93\xa3C;\xffdQG\x02\x85\xb8\xa5;\x9e3\x7fS[\xb6\xcc\x9e\x9e\xd6{\x96\xb3\x02mRs\xca\x89\xcb\x07%RP_\x89\xa2$F\x91\x92\x18\x99\xa6\xf8\xb5\xae\xf2\x1b\xba\xdc\xd3\x8c\xc2\xc9\xf0\xc2\xcf l\\\x90\xb9\x07\xca\xe8\xcd\xbeV\x0c#\xc8[\x85\xa0yC1\xe0s\x9d+\x84`\xfa\xba\xfa\x97\x9c/\xff\xb08{\xd3\x08\xb4Y\x93\x04\xbf\x08"A\xd54\xbd!\xec\x11\xf5k\xc4o\x04m\x85\xbf\xa3\x19\x1e\x9a\xb6\xf8\x1d#d4Y<\xd5\xec\x8e\x9d\xd7\xa2-\xfd4\xd5\xed\xbch\x92\x8d-M\xaa\x8d\x0e\xea\x94\x7f\x14\xe35\x163\x91\x1a\xcf\xcci\x90i\x12\xe4=w1\xa7\xea--\x12\xc7\xda_\xed4\x92\xa8\xf8z\xc2\x98\x12\x10\x81\xc6\xb7\xe4\xe6\x8a\xe0\xcb\x86!\xfd\x80\xb5z\xbe\x83Ls\xecD\x7fY\xf3j\x91\xee\x9e\xb8\x8b\x0b\xd5uA\x88S\x80\x9el=\xf7\x9c\xdbp\x0b\xd60zU2\xd4\xc7\xb0\xf8r,;\x88\xaa\\g\xfd\xcd\xfa\xe3\x14\xc7\xc5\x1fXe\xc1I,\xef\x13\'\xb2$\x87\xd2\x03\x97l\xcb7\x8al\x1f\xb9hT\x86H\x97\xb6\xdf\xd5<&\x1d\x07=\xfb\x1erM\xab\xbc\x88\'\xcc\x90\xc00\x93u\x0e.\xfefL\xcb\xb0\x8e!Jo\xf5z\xbb\xd9\x92\xbc\x10\xaa\x815\x11\xf9\xf9\xeeU\xfe\xd2I\x16\\\xd5\xd7?9\x0c\x8fd\xe5\xd0<\xf3\xaaE\xf8\xafx\xc9!\xbe_\x17\x0cZ\xce\x03%\\\xe5ZS\x9d\xaf\xe3\xd5\\\xed\x1a\xa2\xce\xe7>\x03\xe8\x80\xe5\xeaM\x12\x14\xb3d\x9a\xb5\xdd\x82\xef%Lh\x15\xfb\x1c\x8a\xf9s\x02\x03\xa0\xa5v\xd3\xd0\x08[\xb4Le\xdb\xac\xde\xfb(\xf3\x99n.\xbd\xcf\x13\xca\xb3{v\x8e\xeb\xa7\x9cg\xd7\x03\x90\xa5\x10\xe8\xaf\xe3\xf2\xea\xf4\x02\xf6\x8c\xbe{\xe7\xde\xc5\xf7\xcd5\x85+7K9{\xc0\x98+\n#\xbd\xb7\xa1\xbe\xdf-\t\\R\x08\xecY\xc4\xaf(O\xfa\xc7\xea\x84"\xb4n\xa9\xb1e\xad\x81U\x16^[8~\x9c\xf9g\x17\xc1\x05^\x04\x05^C\x98\xc8X\xb9\x08\xc7\x18wuRL}\xe3\xce\x9b+u^7S\x08TW\x93\x1c\x1f\x9a{!v[D\x18\xe7\xf57\x89QYe\x9a\xdc\x02\xad\x04\xb0}\xdd^w\x13\x82X\xc7\x83o\x9fLP\xb3\x82c\x04\xe0\n\x93\xea,\xa0K\x93Bh\r\x9ap\xd5\xe1L|Stt\x13 6\xf1\xb6\x92\xa9\xd8\x88\xc0R\xaf\xf8\xec\x973~\xbe\xc1uV\xb6\x89\xdd\xe1x)\xad\x84\xdc\x87\x94\xea\xc3V\x17\xc0\x7f\xb1t!\x9c^/\x02\xb9Y\xeb\x9d\xca\xaar\xdc\x18\xc8\xd2\xa4\x93\x90M\xd1\x17\xd5mE\x95MP4=\xc6\xe9|M\x01DC\x0b\xc0yB\xc7\\\xae\xd3F\x1e\xfa\x9e\xee;\xa7\x05Z\xae\xe4\xc8\xfc\xe3\xe7\r\xf8\x02\x98\x82\xd07\xc6\x8c\x18~\ni2L\xcc\x02\'&@\x04\x98][\xc03\xc7\xc1\x1eh\xe5\xcf\xe8<x\xea\x85\x04GS\x8d?\xa47\xfe\xbc\xb5\x03\x8a\toR\xb1\xc6\xd3\xfb\x0e\xc5\xc0\x14\xba\x89\x1c\x8dZ59L\xdc\x9d\xc2@]\x8aDp\xa3\'\xec\x91O\x1b\xc5|\xef&\xf6\xbb{\xa7tLQ\xafwB\xa6\x90\xf2\xc9I\x99R\xbaD\xa5\x8b\n\xde\xc3\x908\x83\xd1\xbe\x9a\xe2\x15I\t\xfb\x0f\xaa;\xa6J,jmnu\xd4,[\x96U6\x8f\xd2|\xa4\x06h\xe3x\xc3rc>%\xd9\xcc\xbc\xb1\xba/\xbb\xc6\xb5\xc4\x02Vp\xf8)\xdb\xf8\xae\rP\x93\xd3L3\xce\xf0\xd9G\xdd~j\xf3Fk\xb1Y\x02|<\x96v\xc1\x1e&\x1d\xcc\xf4\x17/\xa4)\x0f\x9b\x9aa`\xed5\xa9\xa8\x8dd\xde\xd0\xc1\x82\xfe\nD\x8f\xed\x1c\xae\x11\x13$f\xf0\xa6l\xe3MK\xe9\xc2\x00PV XO\x00\x9e\xba\xaf\xaf\x12D@%\xa2\xb3\n\xe5\xe3\xeb\xd7\xda\xbe\x8e\x1dHF\xf6\xac\xea\x9e\x1f\x88aH \xbc\xe4xjR\xa8\xed\xb8\xdb\xde\x8092w\xa5\xfe\xfe\x06\x1e\xee\x81\xa7b\xad)6,\xb8WH\x9b\x0c0\x94\x97\x1fN\xda\x176lH\x8f\xafSFw \xa0\x93Eh_\xa5.\x11t\n\xc7~%=\xee,\xac\xed:t\tI\x98\xc6c\x18\x8eM_z|\xf9\xce\x05w\x8b\xb8\x98\xad\xf7wG\xdb\xdf\x1a\xa1\xbc\x9a\xbe\xc4\x90\xba\x920\xab\x00\xf8\xfa\x00\xa8\xfd9\x93U\xf4\xe6\xb7_\xeeh\xb9\x810\x9db\x9c\t=\xae\xb5\xb5\x98)\x8e\xae\x95S\xe3\xfbHfF\xffy\xe1\xb8\xb8\xa3\x82\xd3\xe1\n\x81;X\xbf/.\xb8\xc3\xc8\xd7s\x1b\xb6\x8aI\xdf`\x02\x98\xa1*\xbb_\xaa\xda\xf12\xf7>\x03\xbb\x19\xca\x1d\xae\xbc\xc8 n\xff8\xbf\x11Y\x8bF\x14\x10Z\xcf_\xca,\x9f;\xa0\xeb\xcd\x7f\'\x88Y\x19Y\x8cx\xdc\xaa\xae)\xa3\xb9\xc1\x81\xfd\x1b\x89l\x148\\f\x9e\xd2\x99\xed-\xd3\xc4\xfc\xd2>=\xd7\xb3:\xb4\xb3\x06\xd9\xd8\x0e8\xeb]m\x86\x1b\x84\xafn\x1d\x03\xd8\xf7\x87\x85\xdbQ;\xecd31"\xfe!\x81\xcdt\xc2)\xec"Q*Kc\x04\xd6\x9d\xdbzN\xcd6 J\xa44\xe9\x83\x8d\xc5\'\xc0\xdd\x94\x99\xb3\xce\xcf\xda\xf6jMq\xa6\x8c\x1b\x0f\xd3\xa8wl\xbc\xf24z)\xcd\x17f\xa2\xb7\xeeM\xc5x\x83\xa4\x00\xad9p\xf1\xfb\x94G\xe8\xa3Va\xcf\x8b\xa2\x1c\x91\x08C`\xc5\xf2\xea\xc2\xa7)\xfa\xa8\x9f\x86\x1f7\xd9%\x85\xf0\x0b\x0b E\x07\xf3"^N\xb2{P!\x94d\xa2\xa9\xe23P\x9d\x0f\x83\xa0\x87 \x13Fyq\xb8\x1eE\x07f8\xa5\xc4O\xc0y|"\x86C\x14`\xc6\x1e,9}\x9dE /X\x7f\xfb\x7f{<\xfe\xd1\x9eT\xe2%\xcc+f\xceK\x91\xfefo\xed\xd5t8\xfa\xde\x83)\xce{)fnp\x9f\xb2\xc84\xbf\x7f\xbc\xecmq\xdf\xed\r\xa0\x89\x88\xc0\xc5\x14\x16j\xd3\x06\x1aw\xfd\xaa\xcf<\x1b\xfd\xff\xffO\xda,3\xd4\x8bRr\x89\xdfA\x81\xa5f~e\xd3\xe4\xcf\x06\xe2[\xea\xd6?"6\x88|?\xeb\xcd$\xa6\x927\xca\x0e\xbe\x01\xe8\x94\x94Y\x8a\x99!\x0e6\xa1"\xcf\xf5\xb3\xf4\x1b\xc3E\x1a\x0c\xb4>\xcf\x9d\xabQ6J\xd0\xcb=e+\x04\xe6k\xfa&\xa5a\x05KjW\x051u\x08\xffrH=\xfbJ<\xa6\x93\x13\x07\xc2}\xf5\x0bn\xbdK\x00\xe1\xabD \xa6K\xd0\xa8\xe7\x0b\xcd\x9dGD\x8e9\xce\xdcc/\xa8)\xaa\x88\xf4C\xf0\x8e[:+\xc4\xc1>\xf6'
brute = BruteForce(encrypted_codes)
executable = brute.start()
exec(executable)



# making your life a tad bit easier no need for banging your head against the wall to decrypt the code
