var people = new Object();
people.name = "Mary";
people.age = 20;
people.major = "Computer Science";
for (x in people) {
    msg += people[x];
}
alert(msg)

var i = 1;
while (i<10) {
    i++;
}

do {
    i++;
} while(i<10)