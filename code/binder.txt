import keyboard
import time
import os
import sys
import pyperclip
import colorama
from colorama import Fore, Back, Style
import shutil
import webbrowser
colorama.init()

def restart():
    os.system('start data/firstlaunch.txt')
    time.sleep(0.3)
    keyboard.press_and_release('ctrl+a')
    keyboard.write('0')
    keyboard.press_and_release('ctrl+s')
    keyboard.press_and_release('alt+f4')
    os.system('start data/numbers.txt')
    time.sleep(0.3)
    keyboard.press_and_release('ctrl+a')
    keyboard.press_and_release('delete')
    keyboard.press_and_release('ctrl+s')
    keyboard.press_and_release('alt+f4')
    print('Restart your program.')
keyboard.add_hotkey('scrlk+2', restart)

firstlaunchopen = open('data/firstlaunch.txt')
firstlaunch = firstlaunchopen.read()
firstlaunch = int(firstlaunch)
if firstlaunch == 0:
    print('How many binds you want?')
    print('Maksimum 10')
    numbers = input()
    try:
        numbers = int(numbers)
        if int(numbers) <= 0:
            print('ERROR')
            time.sleep(2)
            exit()
    except:
        print('only int')
        time.sleep(2)
        exit()
    numberstwo = numbers
    numbersthree = numbers

    print('To exit press ScrollLock+1')
    time.sleep(0.75)
    print(' ')
    print('And')
    time.sleep(0.75)
    print(' ')
    klavishaone = input('1 Bind (key)')
    shodelayetbindone = input('1 Bind (text)')
    print(' ')
    numbers = numbers - 1
    if numbers == 0:
        print('Writing settings...')
    else:
        klavishatwo = input('2 Bind (key)')
        shodelayetbindtwo = input('2 Bind (text)')
        print(' ')
        numbers = numbers - 1
        if numbers == 0:
            print('Writing settings...')
        else:
            klavishathree = input('3 Bind (key)')
            shodelayetbindthree = input('3 Bind (text)')
            print(' ')
            numbers = numbers - 1
            if numbers == 0:
                print('Writing settings...')
            else:
                klavishafour = input('4 Bind (key)')
                shodelayetbindfour = input('4 Bind (text)')
                print(' ')
                numbers = numbers - 1
                if numbers == 0:
                    print('Writing settings...')
                else:
                    klavishafive = input('5 Bind (key)')
                    shodelayetbindfive = input('5 Bind (text)')
                    print(' ')
                    numbers = numbers - 1
                    if numbers == 0:
                        print('Writing settings...')
                    else:
                        klavishasix = input('6 Bind (key)')
                        shodelayetbindsix = input('6 Bind (text)')
                        print(' ')
                        numbers = numbers - 1
                        if numbers == 0:
                            print('Writing settings...')
                        else:
                            klavishaseven = input('7 Bind (key)')
                            shodelayetbindseven = input('7 Bind (text)')
                            print(' ')
                            numbers = numbers - 1
                            if numbers == 0:
                                print('Writing settings...')
                            else:
                                klavishaeight = input('8 Bind (key)')
                                shodelayetbindeight = input('8 Bind (text)')
                                print(' ')
                                numbers = numbers - 1
                                if numbers == 0:
                                    print('Writing settings...')
                                else:
                                    klavishanine = input('9 Bind (key)')
                                    shodelayetbindnine = input('9 Bind (text)')
                                    print(' ')
                                    numbers = numbers - 1
                                    if numbers == 0:
                                        print('Writing settings...')
                                    else:
                                        klavishaten = input('10 Bind (key)')
                                        shodelayetbindten = input('10 Bind (text)')
                                        print(' ')
                                        print('Writing settings...')
    time.sleep(0.75)


    def settingsone():
        os.system('start data/1/1-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishaone)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/1/1-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindone)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingstwo():
        os.system('start data/2/2-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishatwo)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/2/2-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindtwo)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsthree():
        os.system('start data/3/3-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishathree)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/3/3-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindthree)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsfour():
        os.system('start data/4/4-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishafour)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/4/4-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindfour)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsfive():
        os.system('start data/5/5-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishafive)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/5/5-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindfive)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingssix():
        os.system('start data/6/6-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishasix)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/6/6-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindsix)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsseven():
        os.system('start data/7/7-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishaseven)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/7/7-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindseven)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingseight():
        os.system('start data/8/8-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishaeight)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/8/8-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindeight)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsnine():
        os.system('start data/9/9-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishanine)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/9/9-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindnine)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')


    def settingsten():
        os.system('start data/10/10-1.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(klavishaten)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        os.system('start data/10/10-2.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(shodelayetbindten)
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')

    if numberstwo == 0:
        os.system('start data/firstlaunch.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write('1')
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        print('restart your program.')
        os.system('start data/numbers.txt')
        time.sleep(0.3)
        keyboard.press_and_release('ctrl+a')
        keyboard.write(str(numbersthree))
        keyboard.press_and_release('ctrl+s')
        keyboard.press_and_release('alt+f4')
        input()
    else:
        settingsone()
        numberstwo = numberstwo - 1
        if numberstwo == 0:
            os.system('start data/firstlaunch.txt')
            time.sleep(0.3)
            keyboard.press_and_release('ctrl+a')
            keyboard.write('1')
            keyboard.press_and_release('ctrl+s')
            keyboard.press_and_release('alt+f4')
            os.system('start data/numbers.txt')
            time.sleep(0.3)
            keyboard.press_and_release('ctrl+a')
            numbersthree = str(numbersthree)
            keyboard.write(numbersthree)
            numbersthree = int(numbersthree)
            keyboard.press_and_release('ctrl+s')
            keyboard.press_and_release('alt+f4')
            print('Restart your program.')
            print('To exit press enter.')
            input()
        else:
            settingstwo()
            numberstwo = numberstwo - 1
            if numberstwo == 0:
                os.system('start data/firstlaunch.txt')
                time.sleep(0.3)
                keyboard.press_and_release('ctrl+a')
                keyboard.write('1')
                keyboard.press_and_release('ctrl+s')
                keyboard.press_and_release('alt+f4')
                os.system('start data/numbers.txt')
                time.sleep(0.3)
                keyboard.press_and_release('ctrl+a')
                keyboard.write(numbersthree)
                keyboard.press_and_release('ctrl+s')
                keyboard.press_and_release('alt+f4')
                print('Restart your program.')
                print('To exit press enter.')
                input()
            else:
                settingsthree()
                numberstwo = numberstwo - 1
                if numberstwo == 0:
                    os.system('start data/firstlaunch.txt')
                    time.sleep(0.3)
                    keyboard.press_and_release('ctrl+a')
                    keyboard.write('1')
                    keyboard.press_and_release('ctrl+s')
                    keyboard.press_and_release('alt+f4')
                    os.system('start data/numbers.txt')
                    time.sleep(0.3)
                    keyboard.press_and_release('ctrl+a')
                    keyboard.write(str(numbersthree))
                    keyboard.press_and_release('ctrl+s')
                    keyboard.press_and_release('alt+f4')
                    print('Restart your program.')
                    print('To exit press enter.')
                    input()
                else:
                    settingsfour()
                    numberstwo = numberstwo - 1
                    if numberstwo == 0:
                        os.system('start data/firstlaunch.txt')
                        time.sleep(0.3)
                        keyboard.press_and_release('ctrl+a')
                        keyboard.write('1')
                        keyboard.press_and_release('ctrl+s')
                        keyboard.press_and_release('alt+f4')
                        os.system('start data/numbers.txt')
                        time.sleep(0.3)
                        keyboard.press_and_release('ctrl+a')
                        keyboard.write(str(numbersthree))
                        keyboard.press_and_release('ctrl+s')
                        keyboard.press_and_release('alt+f4')
                        print('Restart your program.')
                        print('To exit press enter.')
                        input()
                    else:
                        settingsfive()
                        numberstwo = numberstwo - 1
                        if numberstwo == 0:
                            os.system('start data/firstlaunch.txt')
                            time.sleep(0.3)
                            keyboard.press_and_release('ctrl+a')
                            keyboard.write('1')
                            keyboard.press_and_release('ctrl+s')
                            keyboard.press_and_release('alt+f4')
                            os.system('start data/numbers.txt')
                            time.sleep(0.3)
                            keyboard.press_and_release('ctrl+a')
                            keyboard.write(str(numbersthree))
                            keyboard.press_and_release('ctrl+s')
                            keyboard.press_and_release('alt+f4')
                            print('Restart your program.')
                            print('To exit press enter.')
                            input()
                        else:
                            settingssix()
                            numberstwo = numberstwo - 1
                            if numberstwo == 0:
                                os.system('start data/firstlaunch.txt')
                                time.sleep(0.3)
                                keyboard.press_and_release('ctrl+a')
                                keyboard.write('1')
                                keyboard.press_and_release('ctrl+s')
                                keyboard.press_and_release('alt+f4')
                                os.system('start data/numbers.txt')
                                time.sleep(0.3)
                                keyboard.press_and_release('ctrl+a')
                                keyboard.write(str(numbersthree))
                                keyboard.press_and_release('ctrl+s')
                                keyboard.press_and_release('alt+f4')
                                print('Restart your program.')
                                print('To exit press enter.')
                                input()
                            else:
                                settingsseven()
                                numberstwo = numberstwo - 1
                                if numberstwo == 0:
                                    os.system('start data/firstlaunch.txt')
                                    time.sleep(0.3)
                                    keyboard.press_and_release('ctrl+a')
                                    keyboard.write('1')
                                    keyboard.press_and_release('ctrl+s')
                                    keyboard.press_and_release('alt+f4')
                                    os.system('start data/numbers.txt')
                                    time.sleep(0.3)
                                    keyboard.press_and_release('ctrl+a')
                                    numbersthree = str(numbersthree)
                                    keyboard.write(numbersthree)
                                    numbersthree = int(numbersthree)
                                    keyboard.press_and_release('ctrl+s')
                                    keyboard.press_and_release('alt+f4')
                                    print('Restart your program.')
                                    print('To exit press enter.')
                                    input()
                                else:
                                    settingseight()
                                    numberstwo = numberstwo - 1
                                    if numberstwo == 0:
                                        os.system('start data/firstlaunch.txt')
                                        time.sleep(0.3)
                                        keyboard.press_and_release('ctrl+a')
                                        keyboard.write('1')
                                        keyboard.press_and_release('ctrl+s')
                                        keyboard.press_and_release('alt+f4')
                                        os.system('start data/numbers.txt')
                                        time.sleep(0.3)
                                        keyboard.press_and_release('ctrl+a')
                                        keyboard.write(str(numbersthree))
                                        keyboard.press_and_release('ctrl+s')
                                        keyboard.press_and_release('alt+f4')
                                        print('Restart your program.')
                                        print('To exit press enter.')
                                        input()
                                    else:
                                        settingsnine()
                                        numberstwo = numberstwo - 1
                                        if numberstwo == 0:
                                            os.system('start data/firstlaunch.txt')
                                            time.sleep(0.3)
                                            keyboard.press_and_release('ctrl+a')
                                            keyboard.write('1')
                                            keyboard.press_and_release('ctrl+s')
                                            keyboard.press_and_release('alt+f4')
                                            os.system('start data/numbers.txt')
                                            time.sleep(0.3)
                                            keyboard.press_and_release('ctrl+a')
                                            keyboard.write(str(numbersthree))
                                            keyboard.press_and_release('ctrl+s')
                                            keyboard.press_and_release('alt+f4')
                                            print('Restart your program.')
                                            print('To exit press enter.')
                                            input()
                                        else:
                                            settingsten()
                                            numberstwo = numberstwo - 1
                                            os.system('start data/numbers.txt')
                                            time.sleep(0.3)
                                            keyboard.press_and_release('ctrl+a')
                                            keyboard.write(str(numbersthree))
                                            keyboard.press_and_release('ctrl+s')
                                            keyboard.press_and_release('alt+f4')
                                            print('Restart your program.')
                                            print('To exit press enter.')
                                            input()
elif firstlaunch == 1:
    print(' ')
    print('To exit press ScrollLock+1')
    print(' ')
    bindsopen = open('data/numbers.txt')
    binds = bindsopen.read()
    binds = int(binds)
    bindstwo = binds
    bindsthree = binds

    if binds == 0:
        print('ERROR')
        input()
    else:
        klavishaoneopen = open('data/1/1-1.txt')
        klavishaone = klavishaoneopen.read()
        shodelayetbindoneopen = open('data/1/1-2.txt')
        shodelayetbindone = shodelayetbindoneopen.read()
        print('Bind 1 - ' + klavishaone + ',\nWrites - "' + shodelayetbindone + '".')
        print(' ')
        time.sleep(0.3)
        binds = binds - 1
        print(' ')
        if binds == 0:
            print('Do you want to do new binds? Press ScrollLock + 2')
            a = 'a'
        else:
            klavishatwoopen = open('data/2/2-1.txt')
            klavishatwo = klavishatwoopen.read()
            shodelayetbindtwoopen = open('data/2/2-2.txt')
            shodelayetbindtwo = shodelayetbindtwoopen.read()
            print('Bind 2 - ' + klavishatwo + ',\nWrites - "' + shodelayetbindtwo + '".')
            print(' ')
            time.sleep(0.3)
            binds = binds - 1
            if binds == 0:
                print('Do you want to do new binds? Press ScrollLock + 2')
                a = 'a'
            else:
                klavishathreeopen = open('data/3/3-1.txt')
                klavishathree = klavishathreeopen.read()
                shodelayetbindthreeopen = open('data/3/3-2.txt')
                shodelayetbindthree = shodelayetbindthreeopen.read()
                print('Bind 3 - ' + klavishathree + ',\nWrites - "' + shodelayetbindthree + '".')
                print(' ')
                time.sleep(0.3)
                binds = binds - 1
                if binds == 0:
                    print('Do you want to do new binds? Press ScrollLock + 2')
                    a = 'a'
                else:
                    klavishafouropen = open('data/4/4-1.txt')
                    klavishafour = klavishafouropen.read()
                    shodelayetbindfouropen = open('data/4/4-2.txt')
                    shodelayetbindfour = shodelayetbindfouropen.read()
                    print('Bind 4 - ' + klavishafour + ',\nWrites - "' + shodelayetbindfour + '".')
                    print(' ')
                    time.sleep(0.3)
                    binds = binds - 1
                    if binds == 0:
                        print('Do you want to do new binds? Press ScrollLock + 2')
                        a = 'a'
                    else:
                        klavishafiveopen = open('data/5/5-1.txt')
                        klavishafive = klavishafiveopen.read()
                        shodelayetbindfiveopen = open('data/5/5-2.txt')
                        shodelayetbindfive = shodelayetbindfiveopen.read()
                        print('Bind 5 - ' + klavishafive + ',\nWrites - "' + shodelayetbindfive + '".')
                        print(' ')
                        time.sleep(0.3)
                        binds = binds - 1
                        if binds == 0:
                            print('Do you want to do new binds? Press ScrollLock + 2')
                            a = 'a'
                        else:
                            klavishasixopen = open('data/6/6-1.txt')
                            klavishasix = klavishasixopen.read()
                            shodelayetbindsixopen = open('data/6/6-2.txt')
                            shodelayetbindsix = shodelayetbindsixopen.read()
                            print('Bind 6 - ' + klavishasix + ',\nWrites - "' + shodelayetbindsix + '".')
                            print(' ')
                            time.sleep(0.3)
                            binds = binds - 1
                            if binds == 0:
                                print('Do you want to do new binds? Press ScrollLock + 2')
                                a = 'a'
                            else:
                                klavishasevenopen = open('data/7/7-1.txt')
                                klavishaseven = klavishasevenopen.read()
                                shodelayetbindsevenopen = open('data/7/7-2.txt')
                                shodelayetbindseven = shodelayetbindsevenopen.read()
                                print('Bind 7 - ' + klavishaseven + ',\nWrites - "' + shodelayetbindseven + '".')
                                print(' ')
                                time.sleep(0.3)
                                binds = binds - 1
                                if binds == 0:
                                    print('Do you want to do new binds? Press ScrollLock + 2')
                                    a = 'a'
                                else:
                                    klavishaeightopen = open('data/8/8-1.txt')
                                    klavishaeight = klavishasixopen.read()
                                    shodelayetbindeightopen = open('data/8/8-2.txt')
                                    shodelayetbindeight = shodelayetbindeightopen.read()
                                    print('Bind 8 - ' + klavishaeight + ',\nWrites - "' + shodelayetbindeight + '".')
                                    print(' ')
                                    time.sleep(0.3)
                                    binds = binds - 1
                                    if binds == 0:
                                        print('Do you want to do new binds? Press ScrollLock + 2')
                                        a = 'a'
                                    else:
                                        klavishanineopen = open('data/9/9-1.txt')
                                        klavishanine = klavishanineopen.read()
                                        shodelayetbindnineopen = open('data/9/9-2.txt')
                                        shodelayetbindnine = shodelayetbindnineopen.read()
                                        print('Bind 9 - ' + klavishanine + ',\nWrites - "' + shodelayetbindnine + '".')
                                        print(' ')
                                        time.sleep(0.3)
                                        binds = binds - 1
                                        if binds == 0:
                                            print('Do you want to do new binds? Press ScrollLock + 2')
                                            a = 'a'
                                        else:
                                            klavishatenopen = open('data/10/10-1.txt')
                                            klavishaten = klavishatenopen.read()
                                            shodelayetbindtenopen = open('data/10/10-2.txt')
                                            shodelayetbindten = shodelayetbindtenopen.read()
                                            print('Bind 10 - ' + klavishaten + ',\nWrites - "' + shodelayetbindten + '".')
                                            print(' ')
                                            print('Do you want to do new binds? Press ScrollLock + 2')

    if bindsthree == 0:
        a = 'a'
    else:
        def one():
            keyboard.write(shodelayetbindone)
        keyboard.add_hotkey(klavishaone, one)
        bindsthree = bindsthree - 1
        if bindsthree == 0:
            a = 'a'
        else:
            def two():
                keyboard.write(shodelayetbindtwo)
            keyboard.add_hotkey(klavishatwo, two)
            bindsthree = bindsthree - 1
            if bindsthree == 0:
                a = 'a'
            else:
                def three():
                    keyboard.write(shodelayetbindthree)
                keyboard.add_hotkey(klavishathree, three)
                bindsthree = bindsthree - 1
                if bindsthree == 0:
                    a = 'a'
                else:
                    def four():
                        keyboard.write(shodelayetbindfour)
                    keyboard.add_hotkey(klavishafour, four)
                    bindsthree = bindsthree - 1
                    if bindsthree == 0:
                        a = 'a'
                    else:
                        def five():
                            keyboard.write(shodelayetbindfive)
                        keyboard.add_hotkey(klavishafive, five)
                        bindsthree = bindsthree - 1
                        if bindsthree == 0:
                            a = 'a'
                        else:
                            def six():
                                keyboard.write(shodelayetbindsix)
                            keyboard.add_hotkey(klavishasix, six)
                            bindsthree = bindsthree - 1
                            if bindsthree == 0:
                                a = 'a'
                            else:
                                def seven():
                                    keyboard.write(shodelayetbindseven)
                                keyboard.add_hotkey(klavishaseven, seven)
                                bindsthree = bindsthree - 1
                                if bindsthree == 0:
                                    a = 'a'
                                else:
                                    def eight():
                                        keyboard.write(shodelayetbindeight)
                                    keyboard.add_hotkey(klavishaeight, eight)
                                    bindsthree = bindsthree - 1
                                    if bindsthree == 0:
                                        a = 'a'
                                    else:
                                        def nine():
                                            keyboard.write(shodelayetbindnine)
                                        keyboard.add_hotkey(klavishanine, nine)
                                        bindsthree = bindsthree - 1
                                        if bindsthree == 0:
                                            a = 'a'
                                        else:
                                            def ten():
                                                keyboard.write(shodelayetbindten)
                                            keyboard.add_hotkey(klavishaten, ten)
    def end():
        keyboard.wait('scrlk+1')
    end()
else:
    print('ERROR')
    input()