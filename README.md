                                int(match.group('b'))*256**2 + 
                                 int(match.group('c'))*256 + 
                                 int(match.group('d'))))) 
         print('[+] http://'+re.sub('o', '', str(oct(int(match.group('a')) * 
                                    256**3+int(match.group('b'))*256**2 + 
                                    int(match.group('c'))*256 + 
                                    int(match.group('d')))))+'\n') 
         print('[+] http://'+re.sub('o', '', str(oct(int(match.group('a')))) + 
                                    '.'+str(oct(int(match.group('b'))))+'.' + 
                                    str(oct(int(match.group('c'))))+'.' +
