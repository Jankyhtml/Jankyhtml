class Janky1337:
    def __init__(self):
        self.user_socials = []
    
    def socials(self, socials: list):
        for item in socials:
            if item == 'youtube':
                self.user_socials.append('youtube : Janky')

            elif item == 'discord':
                self.user_socials.append('discord : ⁸⁰⁸ Janky#1337')

            elif item == 'github':
                self.user_socials.append('github : Janky1337')
                
            else:
                self.user_socials.append(f'{item} : unknown')
        return self.user_socials

    def bio(self):
        name      : str = "Azael"
        age       : str = "16"
        birthday  : str = "07/23/2004"
        status    : list = ["student", "developer"]
        languages : list = ["ily", "xanthe", "mwah"]
        return name, age, birthday, status, languages

if __name__ == "__main__":
    client = Janky1337()
    socials = client.socials(['twitter', 'twitch', 'discord', 'instagram'])
    bio = client.bio()
    for i in socials:
        print(i)
    print(bio)
