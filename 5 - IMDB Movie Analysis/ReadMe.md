Hiring Process Analytics

Project Description:

The project aims to analyse the hiring process of a company and provide insights. The analysis will be done using Excel and statistical techniques such as regression analysis and hypothesis testing.

Approach :

First of all I have removed the missing data ( there was only one row containing missing data).

Secondly, I performed outlier analysis where I found there were 3 rows with very high salary and 2 rows with very low salary, so I deleted these 5 rows.

Then started analysing and answering questions.

Tech Stack used:

1. MS Excel

INSIGHTS :

A – Data Cleaning

- Dropped duplicate rows
- Deleted rows that contained blank cells
- Manipulated strings of movie titles and actor names
- Dropped columns that were useless
- Rechecked datatype of all the columns
- Removed outliers on the basis of budget and profit columns

B - Movies with highest profit:

To filter rows on the basis of gender that are hired, we can use COUNTIFS function in MS Excel.

![alt text](https://github.com/hashimali179/Trainity-Projects/blob/main/5%20-%20IMDB%20Movie%20Analysis/Picture2.png)

The above chart shows the relationship between budget and profit. It has a very low positive correlation.

Highest Profit Movie : - Avatar

C - Top 250:

Here is a list of top 250 IMDB movies -

| **The Shawshank Redemption** |
| --- |
| **The Godfather** |
| **The Dark Knight** |
| **The Godfather: Part II** |
| **The Lord of the Rings: The Return of the King** |
| **Pulp Fiction** |
| **Schindler's List** |
| **The Good, the Bad and the Ugly** |
| **Forrest Gump** |
| **Star Wars: Episode V - The Empire Strikes Back** |
| **The Lord of the Rings: The Fellowship of the Ring** |
| **Inception** |
| **Fight Club** |
| **Star Wars: Episode IV - A New Hope** |
| **The Lord of the Rings: The Two Towers** |
| **The Matrix** |
| **One Flew Over the Cuckoo's Nest** |
| **Goodfellas** |
| **City of God** |
| **Seven Samurai** |
| **Saving Private Ryan** |
| **The Silence of the Lambs** |
| **Se7en** |
| **Interstellar** |
| **The Usual Suspects** |
| **American History X** |
| **Modern Times** |
| **Spirited Away** |
| **The Lion King** |
| **Raiders of the Lost Ark** |
| **The Dark Knight Rises** |
| **Back to the Future** |
| **Terminator 2: Judgment Day** |
| **Gladiator** |
| **The Green Mile** |
| **Alien** |
| **Django Unchained** |
| **Apocalypse Now** |
| **The Departed** |
| **Psycho** |
| **Memento** |
| **The Prestige** |
| **Whiplash** |
| **The Lives of Others** |
| **Children of Heaven** |
| **Samsara** |
| **The Pianist** |
| **Star Wars: Episode VI - Return of the Jedi** |
| **American Beauty** |
| **Aliens** |
| **WALL-E** |
| **A Separation** |
| **Braveheart** |
| **Reservoir Dogs** |
| **Oldboy** |
| **Requiem for a Dream** |
| **Das Boot** |
| **Lawrence of Arabia** |
| **Once Upon a Time in America** |
| **Amlie** |
| **Princess Mononoke** |
| **Toy Story 3** |
| **Inside Out** |
| **Toy Story** |
| **The Sting** |
| **Indiana Jones and the Last Crusade** |
| **Good Will Hunting** |
| **Up** |
| **Unforgiven** |
| **Batman Begins** |
| **Inglourious Basterds** |
| **2001: A Space Odyssey** |
| **Amadeus** |
| **L.A. Confidential** |
| **Snatch** |
| **Some Like It Hot** |
| **Scarface** |
| **Eternal Sunshine of the Spotless Mind** |
| **Hoop Dreams** |
| **Room** |
| **Monty Python and the Holy Grail** |
| **The Hunt** |
| **Metropolis** |
| **Downfall** |
| **Raging Bull** |
| **Finding Nemo** |
| **Gone with the Wind** |
| **Captain America: Civil War** |
| **Gran Torino** |
| **A Beautiful Mind** |
| **Die Hard** |
| **How to Train Your Dragon** |
| **The Bridge on the River Kwai** |
| **Pan's Labyrinth** |
| **The Secret in Their Eyes** |
| **The Wolf of Wall Street** |
| **V for Vendetta** |
| **Trainspotting** |
| **On the Waterfront** |
| **Into the Wild** |
| **Lock, Stock and Two Smoking Barrels** |
| **The Big Lebowski** |
| **Incendies** |
| **The Act of Killing** |
| **Blade Runner** |
| **The Thing** |
| **Casino** |
| **Warrior** |
| **Howl's Moving Castle** |
| **The Avengers** |
| **Deadpool** |
| **Jurassic Park** |
| **The Sixth Sense** |
| **Monsters, Inc.** |
| **Pirates of the Caribbean: The Curse of the Black Pearl** |
| **Guardians of the Galaxy** |
| **The Help** |
| **Platoon** |
| **The Martian** |
| **The Bourne Ultimatum** |
| **Rocky** |
| **Gone Girl** |
| **Butch Cassidy and the Sundance Kid** |
| **The Imitation Game** |
| **Million Dollar Baby** |
| **The Truman Show** |
| **Groundhog Day** |
| **No Country for Old Men** |
| **The Revenant** |
| **Shutter Island** |
| **Stand by Me** |
| **Kill Bill: Vol. 1** |
| **12 Years a Slave** |
| **Annie Hall** |
| **Sin City** |
| **The Grand Budapest Hotel** |
| **The Terminator** |
| **Spotlight** |
| **The Best Years of Our Lives** |
| **The Wizard of Oz** |
| **There Will Be Blood** |
| **Prisoners** |
| **The Princess Bride** |
| **Woodstock** |
| **Hotel Rwanda** |
| **Mad Max: Fury Road** |
| **Amores Perros** |
| **Before Sunrise** |
| **The Celebration** |
| **In the Shadow of the Moon** |
| **Donnie Darko** |
| **Elite Squad** |
| **The Sea Inside** |
| **Rush** |
| **Tae Guk Gi: The Brotherhood of War** |
| **Akira** |
| **Jaws** |
| **The Exorcist** |
| **Aladdin** |
| **The Incredibles** |
| **Dances with Wolves** |
| **The Sound of Music** |
| **Rain Man** |
| **Slumdog Millionaire** |
| **The King's Speech** |
| **Catch Me If You Can** |
| **Star Trek** |
| **The Pursuit of Happyness** |
| **Doctor Zhivago** |
| **Black Swan** |
| **District 9** |
| **Young Frankenstein** |
| **Dead Poets Society** |
| **Mystic River** |
| **Ratatouille** |
| **Fiddler on the Roof** |
| **Kill Bill: Vol. 2** |
| **X-Men: Days of Future Past** |
| **JFK** |
| **The Artist** |
| **Sling Blade** |
| **Dallas Buyers Club** |
| **Boyhood** |
| **Bowling for Columbine** |
| **Casino Royale** |
| **Casino Royale** |
| **Sicko** |
| **Shaun of the Dead** |
| **Life of Pi** |
| **The Perks of Being a Wallflower** |
| **A Fistful of Dollars** |
| **Before Sunset** |
| **Central Station** |
| **Her** |
| **Waltz with Bashir** |
| **True Romance** |
| **Persepolis** |
| **Big Fish** |
| **The Straight Story** |
| **Brazil** |
| **In Bruges** |
| **Mulholland Drive** |
| **My Name Is Khan** |
| **Dancer in the Dark** |
| **Magnolia** |
| **Serenity** |
| **Cinderella Man** |
| **Blood In, Blood Out** |
| **Blood Diamond** |
| **The Iron Giant** |
| **Avatar** |
| **E.T. the Extra-Terrestrial** |
| **Shrek** |
| **Iron Man** |
| **Toy Story 2** |
| **Straight Outta Compton** |
| **Taken** |
| **Crouching Tiger, Hidden Dragon** |
| **Walk the Line** |
| **The Fighter** |
| **The Bourne Identity** |
| **Big Hero 6** |
| **My Fair Lady** |
| **Captain Phillips** |
| **Little Miss Sunshine** |
| **The Untouchables** |
| **Crash** |
| **Halloween** |
| **Halloween** |
| **Edward Scissorhands** |
| **The Hobbit: The Desolation of Smaug** |
| **How to Train Your Dragon 2** |
| **The Blues Brothers** |
| **Nightcrawler** |
| **Do the Right Thing** |
| **The Wrestler** |
| **Hot Fuzz** |
| **The Remains of the Day** |
| **Boogie Nights** |
| **The Hateful Eight** |
| **Once** |
| **Glory** |
| **Glory** |
| **Before Midnight** |
| **4 Months, 3 Weeks and 2 Days** |
| **Moon** |
| **Nine Queens** |
| **The Chorus** |
| **The Second Mother** |
| **Letters from Iwo Jima** |
| **The Right Stuff** |
| **Amour** |
| **Ernest & Celestine** |
| **Ed Wood** |
| **The World's Fastest Indian** |
| **Almost Famous** |
| **The Notebook** |
| **Hero** |
| **The Insider** |
| **Children of Men** |
| **Edge of Tomorrow** |

D - Best Directors :

List of Directors with highest average IMDB ratings -

| **Director Name** | **Average IMDB rating** |
| --- | --- |
| **Akira Kurosawa** | 8.7 |
| Tony Kaye | 8.6 |
| Charles Chaplin | 8.6 |
| Ron Fricke | 8.5 |
| Majid Majidi | 8.5 |
| Damien Chazelle | 8.5 |
| Alfred Hitchcock | 8.5 |
| Sergio Leone | 8.433333 |
| Christopher Nolan | 8.425 |
| Asghar Farhadi | 8.4 |

E - Popular Genres:

List of Genres with highest average IMDB ratings -

| **Genre** | **Aerage IMDB Rating** |
| --- | --- |
| **Crime|Drama|Fantasy|Mystery** | 8.5 |
| Adventure|Animation|Drama|Family|Musical | 8.5 |
| Adventure|Animation|Fantasy | 8.4 |
| Adventure|Drama|Thriller|War | 8.4 |
| Documentary|Drama|Sport | 8.3 |
| Biography|Drama|History|Music | 8.3 |
| Adventure|Animation|Comedy|Drama|Family|Fantasy | 8.3 |
| Adventure|Drama|War | 8.25 |
| Drama|Mystery|War | 8.2 |
| Biography|Crime|Documentary|History | 8.2 |

F - Charts:

![alt text](https://github.com/hashimali179/Trainity-Projects/blob/main/5%20-%20IMDB%20Movie%20Analysis/Picture1.png)

The above chart shows the number of users that voted in each decade.

Best actor on the basis of highest average of num\_critic\_reviews :-

| **Actor Name** | **Average of num\_critic\_for\_reviews** |
| --- | --- |
| **Albert Finney** | 750 |

Best actor on the basis of highest average of num\_user\_for\_reviews :-

| **Actor Name** | **Average of num\_user\_for\_reviews** |
| --- | --- |
| **Heather Donahue** | 3400 |

Results –

I have learned how to manipulate data in MS Excel, along with functions, pivot tables and charts & graphs.

This will help me for analyzing and performing EDA in MS Excel.
