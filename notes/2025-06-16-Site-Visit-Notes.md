# Site Visit Notes - 2025-06-16

### Agenda  
- Set build priorities w/Mark and Gregg
- Photo and video all screens
- Measure graphics and text dimensions

#### AV 2 - Woody’s America



#### AV 5 - Dust Bowl Ballads  
- Has attract video
- What did this do?
- Build something based on available assets, using other interactives as visual guide.

#### AV 6 - Music Bar



#### AV 8 - Woody And His World
#####STYLE SHEET  
- Portrait, five thumbnails used for video playback selection.
- Attract text: [ select image below ]  -- change this to something more elegant. Perhaps title banner with title font
- Attract screen: title of thumb 1 appears. Should this instead by the title of the section (1920s Okemah)?
- Video and captions are DISCRETE video files
- "Next" video thumbnail glows/highlights in orange to indicate progressive direction

No navigational icons - everything is tap-to-select

Thumbnails 2 1/16" square  
Orange square boarder around active thumbnail  
HIDE CURSOR  
Grey border behind thumbs approx. 3" height  

Caption black bar approx. 1" height  
Approx 16 1/4" offset from top of screen / approx 6" offset from bottom of screen (bottom line of black bar)  
Main video player approx. 9 1/2" height  
Approx. 5 1/4" offset from top of screen  

Title ribbon approx. 1 1/4" offset from top of screen  
Title ribbon image is "title_background.png"  
Light grey background is "background.png"  
Title font approx 1/2" height  

Approx 1/2" of thumbnail background image visible between top of caption box and main video player

Redesign - inactivity timer triggers attract mode -> hide caption and main video black; replace main video black with still image of Woody from the appropriate time period.  
Cycle through thumbnails with highlighting.  
Change call to action to "Tap an image below to begin"  
Maybe each thumbnail needs a border?

Static Properties

Dynamic Properties:  
- Item ID
- Section Title (Text)New 
- BG Image (Image)
- Thumbnail Image (Image)
- Selection Video (Video)
- Caption Video (Video)
- Idle Image (Image)

##### 01 - 1920s Okemah
- Title order (L -> R)
    - Oklahoma
    - Okemah
    - Woodrow Wilson Guthrie
    - Family Life And Tragedy
    - Musical Roots

##### 02 - 1930s Pampa
- Title order (L -> R)
    - Pampa
    - Marriage
    - The Corncob Trio
    - Sign Painter And Artist
    - To California

##### 03 - 1930s Los Angeles
- Title order (L -> R)
    - On The Radio
    - Plight Of The Oakies
    - Songwriting
    - Signed, Woody Guthrie
    - The Dusty Road

##### 04 - 1940s New York
- Title order (L -> R)
    - New York City
    - In The Recording Studio
    - World War II
    - Bound For Glory
    - The Almanac Singers

##### 05 - 1950s/60s Final Years
- Title order (L -> R)
    - Coney Island And Family Life
    - Children's Songs
    - Huntington's Disease
    - Hospital Years
    - Remembering Woody

#### QUESTIONS
- Burn in captions and remove secondary video (caption block ribbon)?  
- Change [ select image below] look?  
- Make idle title bar the name of the section?  
- Make idle video player an image from the section rather than a black box?  
- Idle time before timeout and reset

#### AV 9 - The Words Are The Music
Make on-screen title match printed title

- At video completion -> auto advance to word cloud
- Word cloud times out to attract screen  
- Tapping animated "VIDEO" sprite or "See what other artists…" asset advance to video scene  
- Use existing transitions and animations as layout guides  
- Fix text overflow (see video) - make paragraph and remove "Song:" when call to action is visible

#### QUESTIONS  
- Need access to all existing visitor submitted lyrics  
- Need GO HOME button?  
- Redo captions in Inspired Artists video?  
- Which email address receives visitor submissions?  

#### AV 10 - Lyric Journal  
- Large database, filtered by word tag  
- One layout for lyric sheet only (default)
    - Secondary layout when doodle included

___Email to: exhibits@woodyguthriecenter.org___

#### Topics list & songs:
__DUST__
- Blowing Down This Road
- Do Re Mi
- Dust Bowl Refugee
- Dust Can't Kill Me
- Dust Pneumonia Blues
- I Ain't Got No Home
- So Long It's Been Good To Know Yuh
- Talking Dust Bowl Blues
- The Great Dust Storm
- Tom Joad
- Vigilante Man

__OKLAHOMA__
- Oklahoma Hills
- Pretty Boy Floyd

__TRAVELIN__
- Baltimore To Washington
- Buoybells For Trenton
- California Stars
- Coney Island
- Go Coney Island
- Grand Coulee Dam
- Hard Travelin'
- I Ain't Got No Home
- I Don’t' Feel At Home On The Bowery No More
- I'm Always On The Go
- I'm Living In Coney's Island
- I'm Shipping Up To Boston
- Los Angeles New Years Flood
- Ludlow Massacre
- Mermaid's Avenue
- My Name Is New York
- Oklahoma Hills
- Old Chisholm Trail
- Old L.A.
- Olde Chykawgoe (Old Chicago)
- Oregon Trail
- Portland Town To Klamath
- Talking Subway Blues
- The New York Trains
- Vanport Flood
- Will Rogers Highway

__BLUES__
- Angel's Bleus
- Dust Pneumonia Blues
- Jackhammer Blues
- Jakewalk Blues
- Mean Talking Blues
- Philadelphia Lawyer
- Talking Dust Bowl Blues
- Talking Subway Blues
- Tea Bag Blues

__NEW YORK__
- Coney Island
- Go Coney Island
- I'm Living In Coney's Island
- Mermaid's Avenue
- My Name Is New York
- Talking Subway Blues
- The New York Trains
- This Land Is Your Land

__LAND__
- 1913 Massacre
- Baltimore To Washington
- Buoybells For Trenton
- California Stars
- Coney Island
- Go Coney Island
- Grand Coulee Dam
- I Don't Feel At Home On The Bowery No More
- I'm Always On The Go
- I've Living I Coney's Island
- I'm Shipping Up To Boston
- Los Angeles New Years Flood
- Ludlow Massacre
- Mermaid's Avenue
- My Name Is New York
- Oklahoma Hills
- Old Chisholm Trail
- Old L.A.
- Olde Chykawgoe (Old Chicago)
- Oregon Trail
- Portland Town To Klamath
- Talking Subway Blues
- The New York Trains
- This Land Is Your Land
- Vanport Flood
- Will Rogers Highway

__RIVER__
- Biggest Thing That Man Has Every Done
- Grand Coulee Dam
- Hard Travelin'
- It Takes A Married Man
- Jackhammer Blues
- New Found Land
- Oregon Trail
- Pastures of Plenty
- Portland Town To Klamath
- Roll on Columbia
- The Song of the Grand Coulee Dam

__PLACES__
- 1913 Massacre
- Baltimore To Washington
- Buoybells For Trenton
- California Stars
- Coney Island
- Go Coney Island
- Grand Coulee Dam
- I Don't Feel At Home On THe Bowery No More
- I'm Always On The Go
- I'm Living In Coney's Island
- I'm Shipping Up To Boston
- Los Angeles New Years Flood
- Ludlow Massacre
- Mermaid's Avenue
- My Name Is New York
- Oklahoma Hills
- Old Chisholm Trail
- Old L.A.
- Olde Chykawgoe (Old Chicago)
- Oregon Trail
- Portland Town To Klamath
- Talking Subway Blues
- The New York Trains
- Vanport Flood
- Will Rogers Highway

__SONG__
- 1913 Massacre
- 50-51
- Aginst Th' Law
- Airline to Heaven
- All Work Together
- All Ya Gotta Do Is Touch Me
- All You Fascists
- Angel's blues
- Another Man's Done gone
- Ashes To Ashes, Dust to Dust
- At My Window Sad & Lonely
- Atom Dance
- Baltimore To Washington
- Be Kind To The Boy On The Road
- Be No Church Tonight
- Been Out On An Ocean Trip
- Better Go Down And Join The Union
- Biggest Thing That Man Has Ever Done
- Birds and Ships
- Black Diamond
- Black Wind Blowing
- Blood of The Lamb
- Blowing Down This Road
- Buoybells For Trenton
- California Stars
- Careless Reckless Love
- Chain of Broken Hearts
- Chorine My Sheba Queen
- Christ for President
- Cleano
- Come When I Call You
- Coney Island
- Dance Around My Atom Fire
- Dead or Alive
- Dig A Hole
- Do Re Mi
- Dry Bed
- Dust Bowl Refugee
- Dust Can't Kill Me
- Dust Pneumonia Blues
- Dying Miner, The
- Eisler on the Go
- Every 100 Years
- Feed of Man
- Fly High
- Folk Song
- From Here On In
- Give Me A Nail
- Go Coney Island
- Go Down To The Water
- Gonna Be A Blackout Tonight
- Gonna Get Through This World
- Gotta Work
- Grand Coulee Dam
- Hammer Ring
- Hangknot, Slipknot
- Hanukah Tree
- Hanuka's Flame
- Happy Joyous Hanuka
- Hard Travelin'
- Harriet Tubman's Ballad
- He And She
- Headdy Down
- Hear You Sing Again
- Heaven
- Hesitating Beauty
- Holy Ground
- Honeyky Hanuka
- Hoodoo Voodoo
- Howdy Little Newlycome
- I Ain't Got No Home
- I don't Feel At Home On The Bowery No More
- I guess I Planted
- I Like To Stay Home With Daddy
- I Want It Now
- I Was A Goner
- I Was Born
- If I Was Everything On Earth
- I'm Always On The Go
- I'm Living In Coney's Island
- I'm Out To Get
- I'm Shipping Up To Boston
- Ingrid Bergman
- It Takes A Married Man
- I've Got to Know
- Jackhammer Blues
- Jakewalk blues
- Jarama Valley
- Jesus Christ
- Jig Along Home
- Jinga Ling
- Joe DiMaggio Done It Again
- Joe Hillstrom
- June 8 1942
- Ladies' Auxiliary
- Listening To The Wind That Blows
- Little Baby Birdy
- Little Suga (Little Saka Sugar)
- Los Angeles New Years Flood
- Ludlow Massacre
- Mail Myself To You
- Many and the Few, The
- Mean Talking Blues
- Meanest Man
- Mermaid's Avenue
- Miss Pavilichenko
- Mister Charlie Lindbergh
- Moichant Marines
- My Battle
- My Flying Saucer
- My Hootenanny
- My Little Seed
- My Name Is New York
- My Peace
- My Thirty Thousand
- New Found Land
- New Multitudes
- New Star
- No Fear
- Oklahoma Hills
- Old Chisholm Trail
- Old Kokaine
- Old L.A.
- Olde chykawgoe (Old Chicago)
- One Big Union
- One By One
- Orange Blossom Ring
- Oregon Trail
- Pass Away
- Pastures of Plenty
- Peejammers I hate
- Philadelphia Lawyer
- Plane Wreck At Los Gatos (Deportee)
- Portland Town To Klamath
- Pretty Boy Floyd
- Put Your Finger In the Air
- Queen Of My Love
- Race You Down The Mountain
- Remember The Mountain Bed
- Revolutionary Mind
- Riding In My Car
- Roll on Columbia
- San Antone Meat House
- Secret Of The Sea
- Ship In The Sky
- Sinking of the Reuben James, The
- So Long It's Been Good To Know Yuh
- Someday Some Morning Sometime
- Stetson Kennedy
- Sweet And Bitter Bowl
- Sweetest Angel
- Talking Dust Bowl Blues
- Talking Empty Bed Blues
- Talking Sailor
- Talking Subway Blues
- Tea Bag Blues
- The Great Dust Storm
- The New York Trains
- The Song of the Grand Coulee Dam
- There's More True Lovers Than One
- This Land Is Your Land
- This Morning I Am Born Again
- Ticky Tock
- Tom Joad
- Union Burying Ground
- Union Maid
- Union Prayer
- Unwelcome Guest, The
- V.D. City
- Vanport Flood
- Vigilante Man
- Way Over Yonder in the Minor Key
- What Are We Waiting On?
- Wheel Of Life
- When I Get Home
- When My Good Ship Went Down
- When the Yanks Go Marching In
- Whereabouts Can I Hide
- Why Oh Why
- Wild Card In The Hole
- Will Rogers Highway
- World's On fire
- You'd Ought To Be Satisfied Now
- Your Sandal String
- Your Smile Cured Me

__LOVE__
- All Ya Gotta Do Is Touch Me
- Angel's blues
- Ashes To Ashes, Dust To Dust
- At My Window Sad & Lonely
- Birds and Ships
- Careless Reckless Love
- Chain of Broken Hearts
- Chorine My Sheba Queen
- Fly High
- Go Down To The Water
- He And She
- Hesitating Beauty
- Listening To The Wind That Blows
- Orange Blossom Ring
- Queen Of My Love
- Remember The Mountain Bed
- Revolutionary Mind
- Secret Of The Sea
- Someday Some Morning Sometime
- Sweet And Bitter Bowl
- Sweetest Angel
- Tea Bag Blues
- There's More Tue Lovers Than One
- World's On Fire
- You'd Ought To Be Satisfied Now
- Your Smile Cured Me

__SHIP__
- Birds and Ships
- Ship In The Sky
- Sinking of the Reuben James, The
- When That Great Ship Went Down

__KIDS__
- All Work Together
- Cleano
- Dry Bed
- Every 100 Years
- Gotta Work
- Hammer Ring
- Howdy Little Newlycome
- I Like To Stay Home With Daddy
- I Want It Now
- I Was Born
- It Takes A Married Man
- Jig Along Home
- Little Baby Birdy
- Little sugar (Little Saka Sugar)
- Mail Myself To You
- My Hootenanny
- My Little Seed
- Peejammers I Hate
- Put Your Finger In the Air
- Race You Down The Mountain
- Riding In My Car
- Ship In The Sky
- Ticky Tock
- Why Oh Why

__UNION__
- 1913 Massacre
- Better Go Down And Join the Union
- Dying Miner, The
- Gotta Work
- Hammer Ring
- Heaven
- I Guess I Planted
- I've Got To Know
- Ladies' Auxiliary
- Ludlow Massacre
- One Big Union
- One By One
- Union Burying Ground
- Union Maid
- Union Prayer

__WORK__
- All Work Together
- Gotta Work
- Heaven

__BIOGRAPHY__
- Eisler on the Go
- Harriet Tubman's Ballad
- Ingrid Bergman
- Jesus Christ
- Joe DiMaggio Done It Again
- Miss Pavilichenko
- Mister Charlie Lindbergh
- My Thirty Thousand
- Pretty Boy Floyd
- Stetson Kennedy
- Tom Joad

__LAW__
- Aginst Th' Law
- Airline to Heaven
- Be Kind To The Boy On The Road
- Black Wind Blowing
- Blood of The Lamb
- Dead or Alive
- Feed of Man
- Give Me A Nail
- Hangknot, Slipknot
- I'm Out To Get
- Jinga Ling
- Joe Hillstrom
- My Thirty Thousand
- Philadelphia Lawyer
- Plane Wreck At Los Gatos (Deportee)
- Pretty Boy Floyd
- Stetson Kennedy
- This Land Is Your Land
- Unwelcome Guest, The
- Vigilante Man

__REFUGEE__
- Do Re Mi
- Dust Bowl Refugee
- Tom Joad

__PROTEST__
- Aginst Th' Law
- Airline to Heaven
- Be Kind To The Boy On The Road
- Black Wind Blowing
- Blood of The Lamb
- Dead or Alive
- Feed of Man
- Give Me A Nail
- Hangknot, Slipknot
- I'm Out To Get
- Jinga Ling
- Joe Hillstrom
- My Thirty Thousand
- Plane Wreck At Los Gatos (Deportee)
- Stetson Kennedy
- This Land Is Your Land
- Unwelcome Guest, The
- Vigilante Man

__WORDS OF PLENTY__
- 50-51
- Another Man's Done Gone
- Atom Dance
- Be No Church Tonight
- Black Diamond
- Christ for President
- Dance Around My Atom Fire
- Folk Song
- From Here On In
- Gonna Get Through This World
- Hanukah Tree
- Hanuka's Flame
- Happy Joyous Hanuka
- Headdy Down
- Hear You Sing Again
- Holy Ground
- Honeyky Hanuka
- Hoodoo Voodoo
- I Was A Goner
- If I Was Everything On Earth
- I'm Living In Coney's Island
- I'm Shipping Up To Boston
- Jakewalk Blues
- June 8 1942
- Many and the Few, The
- Mean Talking Blues
- Meanest Man
- My Battle
- My Flying Saucer
- My Hootenanny
- My Peace
- New Multitudes
- New Star
- No Fear
- Old Kokaine
- Pass Away
- Philadelphia Lawyer
- San Antone Meat House
- Talking Empty Bed Blues
- This Morning I Am Born Again
- V.D. City
- Way Over Yonder in the Minor Key
- Wheel Of Life
- When My Good Ship Went Down
- Whereabouts Can I Hide
- Wild Card In The Hole
- Your Sandal String

__WORLD WAR II__
- All You Fascists
- Been Out On An Ocean Trip
- Come When I Call You
- Dig A Hole
- Gonna Be A Blackout Tonight
- Jarama Valley
- Moichant Marines
- Remember The Mountain Bed
- Ship In The Sky
- Sinking of the Reuben James, The
- Talking Sailor
- What Are We Waiting On?
- When I Get Home
- When the Yanks Go Marching In

#### AV 11 - This Land Is Your Land
Has ATTRACT video (loop). Doesn't appear to be functional

List:
- About the Song
- Annette Funicello and Frankie Avalon
- Arlo Guthrie
- Ginny Tiu
- Glen Campbell
- Hullabaloo Show
- Jimmy Dean
- Kraft Summer Music Hall
- Lyle Lovett, Joe Ely, Guy Clark, and Jol
- Pete Seeger
- Pete Seeger and Bruce Springsteen
- Tennessee Ernie Ford
- The Fabulous Hong Kong Hi De His
- The New Christy Minstrels
- Tom Morello
- Trini Lopez
- Wenzel (German Language Version)

#### AV 12 - Following In Woody’s Footsteps
- Has attract video
- Remake this with new videos based on look of AV11


### PRIORITIES
- AV08 pt 5 & AV06 - equal priority
- Back fill AV08 01 through 04
- AV11 - build for HD1025 stress testing
- AV09
- AV10
- AV05
- AV12
