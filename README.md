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
        image = Image.open('002.png')
        image.show()
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
        image = Image.open('003.png')
        image.show()
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
        image = Image.open('004.png')
        image.show()
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
        image = Image.open('005.png')
        image.show()
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
        image = Image.open('006.png')
        image.show()
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 7:
        print("Squirtle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: When it retracts its long neck into its shell, it squirts out water with vigorous force.")
        image = Image.open('007.png')
        image.show()
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
        image = Image.open('008.png')
        image.show()
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
        image = Image.open('009.png')
        image.show()
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
        image = Image.open('010.png')
        image.show()
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
        image = Image.open('011.png')
        image.show()
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
        image = Image.open('012.png')
        image.show()
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
        image = Image.open('013.png')
        image.show()
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
        image = Image.open('014.png')
        image.show()
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
        image = Image.open('015.png')
        image.show()
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
        image = Image.open('016.png')
        image.show()
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
        image = Image.open('017.png')
        image.show()
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
        image = Image.open('018.png')
        image.show()
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
        image = Image.open('019.png')
        image.show()
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
        image = Image.open('020.png')
        image.show()
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
        image = Image.open('021.png')
        image.show()
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
        image = Image.open('022.png')
        image.show()
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
        image = Image.open('023.png')
        image.show()
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
        image = Image.open('024.png')
        image.show()
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
  
    elif input_string == 25:
        print("Pikachu")
        print("Type: Electric")
        print("Weaknesses: Ground")
        print("Entry: Pikachu that can generate powerful electricity have cheek sacs that are extra soft and super stretchy.")
        image = Image.open('025.png')
        image.show()
        ask_user = input("Would you like to switch your character? Y/N ")
        ask_user = ask_user.upper()
        if ask_user == "Yes" or ask_user == "Y":
            input_string=int(input("Type a number from 1-51 to choose your character: "))
            True
            
        else:
            break
   
    elif input_string == 26:
        print("Raichu")
        print("Type: Electric")
        print("Weaknesses: Ground")
        print("Entry: Its long tail serves as a ground to protect itself from its own high-voltage power.")
        image = Image.open('026.png')
        image.show()
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
        image = Image.open('027.png')
        image.show()
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
        image = Image.open('028.png')
        image.show()
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
        image = Image.open('029.png')
        image.show()
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
        image = Image.open('030.png')
        image.show()
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
        image = Image.open('031.png')
        image.show()
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
        image = Image.open('032.png')
        image.show()
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
        image = Image.open('033.png')
        image.show()
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
        image = Image.open('034.png')
        image.show()
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
        image = Image.open('035.png')
        image.show()
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
        image = Image.open('036.png')
        image.show()
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
        image = Image.open('037.png')
        image.show()
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
        image = Image.open('038.png')
        image.show()
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
        image = Image.open('039.png')
        image.show()
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
        image = Image.open('040.png')
        image.show()
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
        image = Image.open('041.png')
        image.show()
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
        image = Image.open('042.png')
        image.show()
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
        image = Image.open('043.png')
        image.show()
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
        image = Image.open('044.png')
        image.show()
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
        image = Image.open('045.png')
        image.show()
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
        image = Image.open('046.png')
        image.show()
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
        image = Image.open('047.png')
        image.show()
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
        image = Image.open('048.png')
        image.show()
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
        image = Image.open('049.png')
        image.show()
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
        image = Image.open('050.png')
        image.show()
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
        image = Image.open('051.png')
        image.show()
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

input_string_two = random.randint(1,4)
if input_string_two == 1:
        print("Bulbasaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: There is a plant seed on its back right from the day this Pokémon is born. The seed slowly grows larger.")
        image = Image.open('001.png')
        image.show()
        
elif input_string_two == 2:
        print("Ivysaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: When the bulb on its back grows large, it appears to lose the ability to stand on its hind legs.")
        image = Image.open('002.png')
        image.show()
        
elif input_string_two == 3:
        print("Venusaur")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its plant blooms when it is absorbing solar energy. It stays on the move to seek sunlight.")
        image = Image.open('003.png')
        image.show()
        
elif input_string_two == 4:
        print("Charmander")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a preference for hot things. When it rains, steam is said to spout from the tip of its tail.")
        image = Image.open('004.png')
        image.show()
        
elif input_string_two == 5 :
        print("Charmeleon")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It has a barbaric nature. In battle, it whips its fiery tail around and slashes away with sharp claws.")
        image = Image.open('005.png')
        image.show()
        
elif input_string_two == 6:
        print("Charzard")
        print("Type: Fire, Flying")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It spits fire that is hot enough to melt boulders. It may cause forest fires by blowing flames.")
        image = Image.open('006.png')
        image.show()
        
elif input_string_two == 7:
        print("Squirtle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: When it retracts its long neck into its shell, it squirts out water with vigorous force.")
        image = Image.open('007.png')
        image.show()
        
elif input_string_two == 8:
        print("Wartortle")
        print("Type: Water")
        print("Weaknesses: Grass, Electric")
        print("Entry: It is recognized as a symbol of longevity. If its shell has algae on it, that Wartortle is very old.")
        image = Image.open('008.png')
        image.show()
        
elif input_string_two == 9:
        print("Blastoise")
        print("Type: Water")
        print("Weaknesses: Grass, Electic")
        print("Entry: It crushes its foe under its heavy body to cause fainting. In a pinch, it will withdraw inside its shell.")
        image = Image.open('009.png')
        image.show()
        
elif input_string_two == 10: 
        print("Caterpie")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: For protection, it releases a horrible stench from the antenna on its head to drive away enemies.")
        image = Image.open('010.png')
        image.show()
        
elif input_string_two == 11:
        print("Metapod")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It is waiting for the moment to evolve. At this stage, it can only harden, so it remains motionless to avoid attack.")
        image = Image.open('011.png')
        image.show()
        
elif input_string_two == 12:
        print("Butterfree")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: In battle, it flaps its wings at great speed to release highly toxic dust into the air.")
        image = Image.open('012.png')
        image.show()
        
elif input_string_two == 13:
        print("Weedle")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Beware of the sharp stinger on its head. It hides in grass and bushes where it eats leaves.")
        image = Image.open('013.png')
        image.show()
        
elif input_string_two == 14:
        print("Kakuna")
        print("Type: Bug")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: Able to move only slightly. When endangered, it may stick out its stinger and poison its enemy.")
        image = Image.open('014.png')
        image.show()
        
elif input_string_two == 15:
        print("Beedrill")
        print("Type: Bug, Flying")
        print("Weaknesses: Fire, Flying, Rock")
        print("Entry: It has three poisonous stingers on its forelegs and its tail. They are used to jab its enemy repeatedly.")
        image = Image.open('015.png')
        image.show()
        
elif input_string_two == 16:
        print("Pidgey")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Very docile. If attacked, it will often kick up sand to protect itself rather than fight back.")
        image = Image.open('016.png')
        image.show()
        
elif input_string_two == 17:
        print("Pidgeotto")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon is full of vitality. It constantly flies around its large territory in search of prey.")
        image = Image.open('017.png')
        image.show()
        
elif input_string_two == 18:
        print("Pidgeot")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: This Pokémon flies at Mach 2 speed, seeking prey. Its large talons are feared as wicked weapons.")
        image = Image.open('018.png')
        image.show()
        
elif input_string_two == 19:
        print("Fattata")
        print("Type: Normal")
        print("Weaknesses: Fighting")
        print("Entry: Will chew on anything with its fangs. If you see one, you can be certain that 40 more live in the area.")
        image = Image.open('019.png')
        image.show()
        
elif input_string_two == 20:
        print("Radicate")
        print("Type: Normal")
        print("Weaknesses: fighting")
        print("Entry: Its hind feet are webbed. They act as flippers, so it can swim in rivers and hunt for prey.")
        image = Image.open('020.png')
        image.show()
        
elif input_string_two == 21:
        print("Spearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: Inept at flying high. However, it can fly around very fast to protect its territory.")
        image = Image.open('021.png')
        image.show()
        
elif input_string_two == 22:
        print("Fearow")
        print("Type: Normal, Flying")
        print("Weaknesses: Electric, Ice, Rock")
        print("Entry: A Pokémon that dates back many years. If it senses danger, it flies high and away, instantly.")
        image = Image.open('022.png')
        image.show()
        
elif input_string_two == 23:
        print("Ekans")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The older it gets, the longer it grows. At night, it wraps its long body around tree branches to rest.")
        image = Image.open('023.png')
        image.show()
        
elif input_string_two == 24:
        print("Arbok")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The frightening patterns on its belly have been studied. Six variations have been confirmed.")
        image = Image.open('024.png')
        image.show()
        
elif input_string_two == 25:
        print("Pikachu")
        print("Type: Electric")
        print("Weaknesses: Ground")
        print("Entry: Pikachu that can generate powerful electricity have cheek sacs that are extra soft and super stretchy.")
        image = Image.open('025.png')
        image.show()
        
elif input_string_two == 26:
        print("Raichu")
        print("Type: Electric")
        print("Weaknesses: Ground")
        print("Entry: Its long tail serves as a ground to protect itself from its own high-voltage power.")
        image = Image.open('026.png')
        image.show()
        
elif input_string_two == 27:
        print("Sandshrew")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: It loves to bathe in the grit of dry, sandy areas. By sand bathing, the Pokémon rids itself of dirt and moisture clinging to its body.")
        image = Image.open('027.png')
        image.show()
        
elif input_string_two == 28:
        print("Sandslash")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: The drier the area Sandslash lives in, the harder and smoother the Pokémon’s spikes will feel when touched.")
        image = Image.open('028.png')
        image.show()
        
elif input_string_two == 29:
        print("Nidoran-female")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: Females are more sensitive to smells than males. While foraging, they’ll use their whiskers to check wind direction and stay downwind of predators.")
        image = Image.open('029.png')
        image.show()
        
elif input_string_two == 30:
        print("Nidorina")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on its head has atrophied. It’s thought that this happens so Nidorina’s children won’t get poked while their mother is feeding them.")
        image = Image.open('030.png')
        image.show()
        
elif input_string_two == 31:
        print("Nidoqueen")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: Nidoqueen is better at defense than offense. With scales like armor, this Pokémon will shield its children from any kind of attack.")
        image = Image.open('031.png')
        image.show()
        
elif input_string_two == 32:
        print("Nidoran-male")
        print("Type: Poison")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: The horn on a male Nidoran’s forehead contains a powerful poison. This is a very cautious Pokémon, always straining its large ears.")
        image = Image.open('032.png')
        image.show()
        
elif input_string_two == 33:
        print("Nidorino")
        print("Type: Poision")
        print("Weaknesses: Psyhic, Ground")
        print("Entry: With a horn that’s harder than diamond, this Pokémon goes around shattering boulders as it searches for a moon stone.")
        image = Image.open('033.png')
        image.show()
        
elif input_string_two == 34:
        print("Nidoking")
        print("Type: Poison, Ground")
        print("Weaknesses: Water, Psyhic, Ice, Ground")
        print("Entry: When it goes on a rampage, it’s impossible to control. But in the presence of a Nidoqueen it’s lived with for a long time, Nidoking calms down.")
        image = Image.open('034.png')
        image.show()
        
elif input_string_two == 35:
        print("Clefairy")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: It is said that happiness will come to those who see a gathering of Clefairy dancing under a full moon.")
        image = Image.open('035.png')
        image.show()
        
elif input_string_two == 36:
        print("Clefable")
        print("Type: Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: A timid fairy Pokémon that is rarely seen, it will run and hide the moment it senses people.")
        image = Image.open('036.png')
        image.show()
        
elif input_string_two == 37:
        print("Vulpix")
        print("Type: Fire")
        print("Weaknesses:  Water, Ground, Rock")
        print("Entry: While young, it has six gorgeous tails. When it grows, several new tails are sprouted.")
        image = Image.open('037.png')
        image.show()
        
elif input_string_two == 38:
        print("Ninetales")
        print("Type: Fire")
        print("Weaknesses: Water, Ground, Rock")
        print("Entry: It is said to live 1,000 years, and each of its tails is loaded with supernatural powers.")
        image = Image.open('038.png')
        image.show()
        
elif input_string_two == 39:
        print("Jigglypuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: Jigglypuff has top-notch lung capacity, even by comparison to other Pokémon. It won’t stop singing its lullabies until its foes fall asleep.")
        image = Image.open('039.png')
        image.show()
        
elif input_string_two == 40:
        print("Wigglytuff")
        print("Type: Normal, Fairy")
        print("Weaknesses: Steel, Poison")
        print("Entry: The more air it takes in, the more it inflates. If opponents catch it in a bad mood, it will inflate itself to an enormous size to intimidate them.")
        image = Image.open('040.png')
        image.show()
        
elif input_string_two == 41:
        print("Zubat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It emits ultrasonic waves from its mouth to check its surroundings. Even in tight caves, Zubat flies around with skill.")
        image = Image.open('041.png')
        image.show()
        
elif input_string_two ==  42:
        print("Golbat")
        print("Type: Poison, Flying")
        print("Weaknesses: Psyhic, Electric, Ice, Rock")
        print("Entry: It loves to drink other creatures’ blood. It’s said that if it finds others of its kind going hungry, it sometimes shares the blood it’s gathered.")
        image = Image.open('042.png')
        image.show()
        
elif input_string_two == 43:
        print("Oddish")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: If exposed to moonlight, it starts to move. It roams far and wide at night to scatter its seeds.")
        image = Image.open('043.png')
        image.show()
        
elif input_string_two == 44:
        print("Gloom")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: Its pistils exude an incredibly foul odor. The horrid stench can cause fainting at a distance of 1.25 miles.")
        image = Image.open('044.png')
        image.show()
        
elif input_string_two == 45:
        print("Vileplume")
        print("Type: Grass, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Ice")
        print("Entry: It has the world’s largest petals. With every step, the petals shake out heavy clouds of toxic pollen.")
        image = Image.open('045.png')
        image.show()
        
elif input_string_two == 46:
        print("Paras")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: Burrows under the ground to gnaw on tree roots. The mushrooms on its back absorb most of the nutrition.")
        image = Image.open('046.png')
        image.show()
        
elif input_string_two == 47:
        print("Parasect")
        print("Type: Bug, Grass")
        print("Weaknesses: Fire, Flying, Ice, Poison, Rock, Bug")
        print("Entry: The bug host is drained of energy by the mushroom on its back. The mushroom appears to do all the thinking.")
        image = Image.open('047.png')
        image.show()
        
elif input_string_two == 48:
        print("Venonat")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: Its large eyes act as radar. In a bright place, you can see that they are clusters of many tiny eyes.")
        image = Image.open('048.png')
        image.show()
        
elif input_string_two == 49:
        print("Venomoth")
        print("Type: Bug, Poison")
        print("Weaknesses: Fire, Psyhic, Flying, Rock")
        print("Entry: The powdery scales on its wings are hard to remove from skin. They also contain poison that leaks out on contact.")
        image = Image.open('049.png')
        image.show()
        
elif input_string_two == 50:
        print("Diglett")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: If a Diglett digs through a field, it leaves the soil perfectly tilled and ideal for planting crops.")
        image = Image.open('050.png')
        image.show()
        
elif input_string_two == 51:
        print("Dugtrio")
        print("Type: Ground")
        print("Weaknesses: Water, Grass, Ice")
        print("Entry: A team of Diglett triplets. It triggers huge earthquakes by burrowing 60 miles underground.")
        image = Image.open('051.png')
        image.show()

print()

#battle simulator

Bulbasaur = grass
Ivysaur = grass
Venusaur = grass
Charmander = fire
Charmeleon = fire
Charzard = fire
Squitle = water
8 = water
9 = water
10 = bug
11 = bug
12 = bug
13 = bug
14 = bug
15 = bug
16 = normal
17 = normal
18 = normal
19 = normal
20 = normal
21 = normal
22 = normal
23 = poison
24 = poison
25 = electric
26 = electric
27 = ground
28 = ground
29 = poison
30 = poison
31 = posion
32 = poison
33 = poison
34 = poison
35 = fairy
36 = fairy
37 = fire
38 = fire
39 = normal
40 = normal
41 = poison
42 = poison
43 = grass
44 = grass
45 = grass
46 = bug
47 = bug
48 = bug
49 = bug
50 = ground
51 = ground


grass water fire bug normal poison electric fairy

if input_string == grass
   

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

