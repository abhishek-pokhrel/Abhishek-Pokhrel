module main

aboutMe :: struct {
  pronouns :: string[];
  languages :: string[];
  hobbies :: string[];
  funFact :: string;
}

main :: func(): void {
  abhishek :: aboutMe = {
    pronouns: ["He", "Him"],
    languages: ["C", "JS", "Python", "SQL"],
    hobbies: ["Coding", "Gaming", "Exploring"],
    funFact: "I actually touch grass!"
  };

  println "Pronouns: ${ethan.pronouns}";
  println "Languages I Know: ${ethan.languages}";
  println "My Hobbies: ${abhishek.hobbies}";
  println "Fun Fact: ${abhishek.funFact}";
}
