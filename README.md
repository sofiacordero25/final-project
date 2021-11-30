#final project: pokedex and battle simulator
#sofia cordero, matt burkhimer, & nazli iclal karaman

#choosing the user's character
 from PIL import Image
input_string=int(input("Type a number from 1-51 to choose your character: "))
while True:
    if input_string == 1:
        print("Bulbasaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: There is a plant seed on its back right from the day this Pokémon is born. The seed slowly grows larger.")
        image = Image.open('001.png')
        image.show()
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
           
  
    elif input_string == 2:
        print("Ivysaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: When the bulb on its back grows large, it appears to lose the ability to stand on its hind legs.")
        b = open('002.jpg')
        print(b)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 3:
        print("Venusaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its plant blooms when it is absorbing solar energy. It stays on the move to seek sunlight.")
        c = open('003.jpg')
        print(c)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 4:
        print("Charmander")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a preference for hot things. When it rains, steam is said to spout from the tip of its tail.")
        d = open('004.jpg')
        print(d)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 5 :
        print("Charmeleon")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a barbaric nature. In battle, it whips its fiery tail around and slashes away with sharp claws.")
        e = open('005.jpg')
        print(e)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 6:
        print("Charzard")
        print("Type: Fire, Flying")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It spits fire that is hot enough to melt boulders. It may cause forest fires by blowing flames.")
        f = open('006.jpg')
        print(f)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 7:
        print("Squitle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: When it retracts its long neck into its shell, it squirts out water with vigorous force.")
        g = open('007.jpg')
        print(g)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 8:
        print("Wartortle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: It is recognized as a symbol of longevity. If its shell has algae on it, that Wartortle is very old.")
        h = open('008.jpg')
        print(h)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 9:
        print("Blastoise")
        print("Type: Water")
        print("Weaknesses: Grass, Electic")
        print("Entry: It crushes its foe under its heavy body to cause fainting. In a pinch, it will withdraw inside its shell.")
        i = open('009.jpg')
        print(i)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 10: 
        print("Caterpie")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: For protection, it releases a horrible stench from the antenna on its head to drive away enemies.")
        j = open('010.jpg')
        print(j)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break

    elif input_string == 11:
        print("Metapod")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It is waiting for the moment to evolve. At this stage, it can only harden, so it remains motionless to avoid attack.")
        k = open('011.jpg')
        print(k)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 12:
        print("Butterfree")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: In battle, it flaps its wings at great speed to release highly toxic dust into the air.")
        l = open('012.jpg')
        print(l)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 13:
        print("Weedle")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Beware of the sharp stinger on its head. It hides in grass and bushes where it eats leaves.")
        m = open('013.jpg')
        print(m)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 14:
        print("Kakuna")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Able to move only slightly. When endangered, it may stick out its stinger and poison its enemy.")
        n = open('014.jpg')
        print(n)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 15:
        print("Beedrill")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It has three poisonous stingers on its forelegs and its tail. They are used to jab its enemy repeatedly.")
        o = open('015.jpg')
        print(o)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 16:
        print("Pidgey")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Very docile. If attacked, it will often kick up sand to protect itself rather than fight back.")
        p = open('016.jpg')
        print(p)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 17:
        print("Pidgeotto")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon is full of vitality. It constantly flies around its large territory in search of prey.")
        q = open('017.jpg')
        print(q)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 18:
        print("Pidgeot")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon flies at Mach 2 speed, seeking prey. Its large talons are feared as wicked weapons.")
        r = open('018.jpg')
        print(r)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 19:
        print("Fattata")
        print("Type: Normal")
        print("Weaknesses: Fighting")
        print("Entry: Will chew on anything with its fangs. If you see one, you can be certain that 40 more live in the area.")
        s = open('019.jpg')
        print(s)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 20:
        print("Radicate")
        print("Type: Normal")
        print("Weaknesses: fighting")
        print("Entry: Its hind feet are webbed. They act as flippers, so it can swim in rivers and hunt for prey.")
        t = open('020.jpg')
        print(t)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 21:
        print("Spearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Inept at flying high. However, it can fly around very fast to protect its territory.")
        u = open('021.jpg')
        print(u)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 22:
        print("Fearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: A Pokémon that dates back many years. If it senses danger, it flies high and away, instantly.")
        v = open('022.jpg')
        print(v)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 23:
        print("Ekans")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The older it gets, the longer it grows. At night, it wraps its long body around tree branches to rest.")
        w = open('023.jpg')
        print(w)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string== 24:
        print("Arbok")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The frightening patterns on its belly have been studied. Six variations have been confirmed.")
        x = open('024.jpg')
        print(x)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 25:
        print("pikachu")
        print("Type: electric")
        print("Weaknesses: Ground")
        print("Entry: Pikachu that can generate powerful electricity have cheek sacs that are extra soft and super stretchy.")
        y = open('025.jpg')
        print(y)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
   
    elif input_string == 26:
        print("raichu")
        print("Type: electric")
        print("Weaknesses: Ground")
        print("Entry: Its long tail serves as a ground to protect itself from its own high-voltage power.")
        z = open('026.jpg')
        print(z)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 27:
        print("Sandshrew")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: It loves to bathe in the grit of dry, sandy areas. By sand bathing, the Pokémon rids itself of dirt and moisture clinging to its body.")
        aa = open('027.jpg')
        print(aa)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 28:
        print("Sandslash")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: The drier the area Sandslash lives in, the harder and smoother the Pokémon’s spikes will feel when touched.")
        ab = open('028.jpg')
        print(ab)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 29:
        print("Nidoran-female")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: Females are more sensitive to smells than males. While foraging, they’ll use their whiskers to check wind direction and stay downwind of predators.")
        ac = open('029.jpg')
        print(ac)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 30:
        print("Nidorina")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on its head has atrophied. It’s thought that this happens so Nidorina’s children won’t get poked while their mother is feeding them.")
        ad = open('030.jpg')
        print(ad)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 31:
        print("Nidoqueen")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: Nidoqueen is better at defense than offense. With scales like armor, this Pokémon will shield its children from any kind of attack.")
        ae = open('031.jpg')
        print(ae)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 32:
        print("Nidoran-male")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on a male Nidoran’s forehead contains a powerful poison. This is a very cautious Pokémon, always straining its large ears.")
        af = open('032.jpg')
        print(af)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 33:
        print("Nidorino")
        print("Type: Poision")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: With a horn that’s harder than diamond, this Pokémon goes around shattering boulders as it searches for a moon stone.")
        ag = open('033.jpg')
        print(ag)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 34:
        print("Nidoking")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: When it goes on a rampage, it’s impossible to control. But in the presence of a Nidoqueen it’s lived with for a long time, Nidoking calms down.")
        ah = open('034.jpg')
        print(ah)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 35:
        print("Clefairy")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: It is said that happiness will come to those who see a gathering of Clefairy dancing under a full moon.")
        ai = open('035.jpg')
        print(ai)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 36:
        print("Clefable")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: A timid fairy Pokémon that is rarely seen, it will run and hide the moment it senses people.")
        aj = open('036.jpg')
        print(aj)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 37:
        print("Vulpix")
        print("Type: Fire")
        print("Weaknesses:  Water, Ground, Rock")
        print("Entry: While young, it has six gorgeous tails. When it grows, several new tails are sprouted.")
        ak = open('037.jpg')
        print(ak)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 38:
        print("Ninetales")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It is said to live 1,000 years, and each of its tails is loaded with supernatural powers.")
        al = open('038.jpg')
        print(al)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 39:
        print("Jigglypuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: Jigglypuff has top-notch lung capacity, even by comparison to other Pokémon. It won’t stop singing its lullabies until its foes fall asleep.")
        am = open('039.jpg')
        print(am)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 40:
        print("Wigglytuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: The more air it takes in, the more it inflates. If opponents catch it in a bad mood, it will inflate itself to an enormous size to intimidate them.")
        an = open('040.jpg')
        print(an)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 41:
        print("Zubat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It emits ultrasonic waves from its mouth to check its surroundings. Even in tight caves, Zubat flies around with skill.")
        ao = open('041.jpg')
        print(ao)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string ==  42:
        print("Golbat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It loves to drink other creatures’ blood. It’s said that if it finds others of its kind going hungry, it sometimes shares the blood it’s gathered.")
        ap = open('042.jpg')
        print(ap)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 43:
        print("Oddish")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: If exposed to moonlight, it starts to move. It roams far and wide at night to scatter its seeds.")
        aq = open('043.jpg')
        print(aq)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 44:
        print("Gloom")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its pistils exude an incredibly foul odor. The horrid stench can cause fainting at a distance of 1.25 miles.")
        ar = open('044.jpg')
        print(ar)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 45:
        print("Vileplume")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: It has the world’s largest petals. With every step, the petals shake out heavy clouds of toxic pollen.")
        as = open('045.jpg')
        print(as)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 46:
        print("Paras")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: Burrows under the ground to gnaw on tree roots. The mushrooms on its back absorb most of the nutrition.")
        at = open('046.jpg')
        print(at)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 47:
        print("Parasect")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: The bug host is drained of energy by the mushroom on its back. The mushroom appears to do all the thinking.")
        au = open('047.jpg')
        print(au)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 48:
        print("Venonat")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: Its large eyes act as radar. In a bright place, you can see that they are clusters of many tiny eyes.")
        av = open('048.jpg')
        print(av)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 49:
        print("Venomoth")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: The powdery scales on its wings are hard to remove from skin. They also contain poison that leaks out on contact.")
        aw = open('049.jpg')
        print(aw)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 50:
        print("Diglett")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: If a Diglett digs through a field, it leaves the soil perfectly tilled and ideal for planting crops.")
        ax = open('050.jpg')
        print(ax)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 51:
        print("Dugtrio")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: A team of Diglett triplets. It triggers huge earthquakes by burrowing 60 miles underground.")
        ay = open('051.jpg')
        print(ay)
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
    
    else:
        print("You did not enter a valid option.")
        print("Please try again!")
        input_string=int(input("Type a number from 1-51 to choose your character: "))
    
        #to restart the code

print()
        
#choosing the computer's character (at random)

print("The computer's character is...")

import random

input_string = random.randint(1,4)
if input_string == 1:
        print("Bulbasaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: There is a plant seed on its back right from the day this Pokémon is born. The seed slowly grows larger.")
        a = open('001.jpg')
        print(a)
        
elif input_string == 2:
        print("Ivysaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: When the bulb on its back grows large, it appears to lose the ability to stand on its hind legs.")
        b = open('002.jpg')
        print(b)
        
elif input_string == 3:
        print("Venusaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its plant blooms when it is absorbing solar energy. It stays on the move to seek sunlight.")
        c = open('003.jpg')
        print(c)
        
elif input_string == 4:
        print("Charmander")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a preference for hot things. When it rains, steam is said to spout from the tip of its tail.")
        d = open('004.jpg')
        print(d)
        
elif input_string == 5 :
        print("Charmeleon")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a barbaric nature. In battle, it whips its fiery tail around and slashes away with sharp claws.")
        e = open('005.jpg')
        print(e)
        
elif input_string == 6:
        print("Charzard")
        print("Type: Fire, Flying")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It spits fire that is hot enough to melt boulders. It may cause forest fires by blowing flames.")
        f = open('006.jpg')
        print(f)
        
elif input_string == 7:
        print("Squitle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: When it retracts its long neck into its shell, it squirts out water with vigorous force.")
        g = open('007.jpg')
        print(g)
        
elif input_string == 8:
        print("Wartortle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: It is recognized as a symbol of longevity. If its shell has algae on it, that Wartortle is very old.")
        h = open('008.jpg')
        print(h)
        
elif input_string == 9:
        print("Blastoise")
        print("Type: Water")
        print("Weaknesses: Grass, Electic")
        print("Entry: It crushes its foe under its heavy body to cause fainting. In a pinch, it will withdraw inside its shell.")
        i = open('009.jpg')
        print(i)
        
elif input_string == 10: 
        print("Caterpie")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: For protection, it releases a horrible stench from the antenna on its head to drive away enemies.")
        j = open('010.jpg')
        print(j)
        
elif input_string == 11:
        print("Metapod")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It is waiting for the moment to evolve. At this stage, it can only harden, so it remains motionless to avoid attack.")
        k = open('011.jpg')
        print(k)
        
elif input_string == 12:
        print("Butterfree")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: In battle, it flaps its wings at great speed to release highly toxic dust into the air.")
        l = open('012.jpg')
        print(l)
        
elif input_string == 13:
        print("Weedle")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Beware of the sharp stinger on its head. It hides in grass and bushes where it eats leaves.")
        m = open('013.jpg')
        print(m)
        
elif input_string == 14:
        print("Kakuna")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Able to move only slightly. When endangered, it may stick out its stinger and poison its enemy.")
        n = open('014.jpg')
        print(n)
        
elif input_string == 15:
        print("Beedrill")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It has three poisonous stingers on its forelegs and its tail. They are used to jab its enemy repeatedly.")
        o = open('015.jpg')
        print(o)
        
elif input_string == 16:
        print("Pidgey")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Very docile. If attacked, it will often kick up sand to protect itself rather than fight back.")
        
elif input_string == 17:
        print("Pidgeotto")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon is full of vitality. It constantly flies around its large territory in search of prey.")
        
elif input_string == 18:
        print("Pidgeot")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon flies at Mach 2 speed, seeking prey. Its large talons are feared as wicked weapons.")
        
elif input_string == 19:
        print("Fattata")
        print("Type: Normal")
        print("Weaknesses: Fighting")
        print("Entry: Will chew on anything with its fangs. If you see one, you can be certain that 40 more live in the area.")
        
elif input_string == 20:
        print("Radicate")
        print("Type: Normal")
        print("Weaknesses: fighting")
        print("Entry: Its hind feet are webbed. They act as flippers, so it can swim in rivers and hunt for prey.")
        
elif input_string == 21:
        print("Spearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Inept at flying high. However, it can fly around very fast to protect its territory.")
        
elif input_string == 22:
        print("Fearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: A Pokémon that dates back many years. If it senses danger, it flies high and away, instantly.")
        
elif input_string == 23:
        print("Ekans")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The older it gets, the longer it grows. At night, it wraps its long body around tree branches to rest.")
        
elif input_string== 24:
        print("Arbok")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The frightening patterns on its belly have been studied. Six variations have been confirmed.")
        
elif input_string == 25:
        print("pikachu")
        print("Type: electric")
        print("Weaknesses: Ground")
        print("Entry: Pikachu that can generate powerful electricity have cheek sacs that are extra soft and super stretchy.")
        
elif input_string == 26:
        print("raichu")
        print("Type: electric")
        print("Weaknesses: Ground")
        print("Entry: Its long tail serves as a ground to protect itself from its own high-voltage power.")
        
elif input_string == 27:
        print("Sandshrew")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: It loves to bathe in the grit of dry, sandy areas. By sand bathing, the Pokémon rids itself of dirt and moisture clinging to its body.")
        
elif input_string == 28:
        print("Sandslash")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: The drier the area Sandslash lives in, the harder and smoother the Pokémon’s spikes will feel when touched.")
        
elif input_string == 29:
        print("Nidoran-female")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: Females are more sensitive to smells than males. While foraging, they’ll use their whiskers to check wind direction and stay downwind of predators.")
        
elif input_string == 30:
        print("Nidorina")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on its head has atrophied. It’s thought that this happens so Nidorina’s children won’t get poked while their mother is feeding them.")
        
elif input_string == 31:
        print("Nidoqueen")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: Nidoqueen is better at defense than offense. With scales like armor, this Pokémon will shield its children from any kind of attack.")
        
elif input_string == 32:
        print("Nidoran-male")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on a male Nidoran’s forehead contains a powerful poison. This is a very cautious Pokémon, always straining its large ears.")
        
elif input_string == 33:
        print("Nidorino")
        print("Type: Poision")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: With a horn that’s harder than diamond, this Pokémon goes around shattering boulders as it searches for a moon stone.")
        
elif input_string == 34:
        print("Nidoking")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: When it goes on a rampage, it’s impossible to control. But in the presence of a Nidoqueen it’s lived with for a long time, Nidoking calms down.")
        
elif input_string == 35:
        print("Clefairy")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: It is said that happiness will come to those who see a gathering of Clefairy dancing under a full moon.")
        
elif input_string == 36:
        print("Clefable")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: A timid fairy Pokémon that is rarely seen, it will run and hide the moment it senses people.")
        
elif input_string == 37:
        print("Vulpix")
        print("Type: Fire")
        print("Weaknesses:  Water, Ground, Rock")
        print("Entry: While young, it has six gorgeous tails. When it grows, several new tails are sprouted.")
        
elif input_string == 38:
        print("Ninetales")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It is said to live 1,000 years, and each of its tails is loaded with supernatural powers.")
        
elif input_string == 39:
        print("Jigglypuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: Jigglypuff has top-notch lung capacity, even by comparison to other Pokémon. It won’t stop singing its lullabies until its foes fall asleep.")
        
elif input_string == 40:
        print("Wigglytuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: The more air it takes in, the more it inflates. If opponents catch it in a bad mood, it will inflate itself to an enormous size to intimidate them.")
        
elif input_string == 41:
        print("Zubat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It emits ultrasonic waves from its mouth to check its surroundings. Even in tight caves, Zubat flies around with skill.")
        
elif input_string ==  42:
        print("Golbat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It loves to drink other creatures’ blood. It’s said that if it finds others of its kind going hungry, it sometimes shares the blood it’s gathered.")
        
elif input_string == 43:
        print("Oddish")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: If exposed to moonlight, it starts to move. It roams far and wide at night to scatter its seeds.")
        
elif input_string == 44:
        print("Gloom")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its pistils exude an incredibly foul odor. The horrid stench can cause fainting at a distance of 1.25 miles.")
        
elif input_string == 45:
        print("Vileplume")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: It has the world’s largest petals. With every step, the petals shake out heavy clouds of toxic pollen.")
        
elif input_string == 46:
        print("Paras")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: Burrows under the ground to gnaw on tree roots. The mushrooms on its back absorb most of the nutrition.")
        
elif input_string == 47:
        print("Parasect")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: The bug host is drained of energy by the mushroom on its back. The mushroom appears to do all the thinking.")
        au = open('047.jpg')
        print(au)
        
elif input_string == 48:
        print("Venonat")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: Its large eyes act as radar. In a bright place, you can see that they are clusters of many tiny eyes.")
        av = open('048.jpg')
        print(av)
        
elif input_string == 49:
        print("Venomoth")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: The powdery scales on its wings are hard to remove from skin. They also contain poison that leaks out on contact.")
        aw = open('049.jpg')
        print(aw)
        
elif input_string == 50:
        print("Diglett")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: If a Diglett digs through a field, it leaves the soil perfectly tilled and ideal for planting crops.")
        ax = open('050.jpg')
        print(ax)
        
elif input_string == 51:
        print("Dugtrio")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: A team of Diglett triplets. It triggers huge earthquakes by burrowing 60 miles underground.")
        ay = open('051.jpg')
        print(ay)



#grass < fire, flying ice, poison, bug
#fire < water, ground, rock
#water < grass, electric
#bug < fire, flying, rock
#normal < fighting
#flying < rock, steel, electric
#poison < psyhic, ground
#electric < ground
#ground < water, grass, ice
#fairy < steel, poison

