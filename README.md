# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
start a django project and create templates folder
### Step 2:
then write the code in html files and assign path and edit views 
## Code:
#map.html:
```<!DOCTYPE html>
<html>
    <head>
        <title>alagappa university Image Map</title>
    </head>
    <body>
        <h1 align='center'> Map of alagappa university karaikudi</h1>
        <h2  align='left'>Address:</h2>
        <h3 align='left'>College Rd, Alagappa Puram, Karaikudi, Tamil Nadu 630003</h3>
        <img src = "/static/images/map.png" height="700" width="1500" align="center" usemap="#collegemap">
        <map name="collegemap">
            <area  alt="" title="cadd lab" href="caddlab.html" shape="poly" coords="745,218,699,230,669,303,734,316,760,282" style="outline:none;" target="_self" />
            <area  alt="" title="cse department" href="cse.html" shape="poly" coords="1243,375,1182,455,1197,559,1281,610,1380,511" style="outline:none;" target="_self"  />
            <area  alt="" title="ece department" href="ece.html" shape="poly" coords="1043,658,930,613,888,698,907,756,983,734,1011,745" style="outline:none;" target="_self"  />
            <area  alt="" title="library" href="lib.html" shape="poly" coords="449,529,401,583,485,627,543,590,516,523" style="outline:none;" target="_self"     />
            <area  alt="" title="Mechanical department" href="mech.html" shape="poly" coords="305,172,517,164,529,296,288,313" style="outline:none;" target="_self"     />
        </map>
</body>
</html>```
#cse.html
<!DOCTYPE html>
<html>
	<head>
		<title>CSE department</title>
	</head>
	<body>
 <center><img src = "/static/images/cse.png" height="250" width="600" align="center"></center>c
 <h2 align="center">cse department</h2>
 <p>
We the Department of Computer Science and Engineering ever since 1984 strive to create an ambience of academic excellence in which new ideas, research and scholarship flourish and from which the leaders and innovators of tomorrow emerge 
 
Accredited by the National Board of Accrediation for a period of 2 years, the computer science and engineering is one of the most eminent programme in GCT. The four year under graduate programme in Computer Science is intended to train the students in both advanced areas in the core courses and specialized topics in the emerging technology. 
 
It has become the pool for research scholars with  inclusion of M.Phil and PhD courses in 1992. We have a team of highly qualified and dedicated teaching faculty well supported by a  group of Techincal support staff for keeping campus vibrant as a temple of knowledge under a self imposed discipline by one and all. 
 
Our future techies, scientists, executives, entrepreneurs are nurtured and encouraged with creative approach. It has excellent infrastructure and facilities for students. It is the endeavor of the management to periodically migrate to the latest software and hardware to keep pace with ever changing needs with the industries so that our students come out with latest knowledge in both software and hardware 
 
The necessary licensed software and internet facilities are available for all students round the clock. Besides imparting theoretical knowledge, the curriculum stresses on developing analytical stills, communication, problem solving, and teamwork abilities 
</p>
#ece.html:
<!DOCTYPE html>
<html>
	<head>
		<title>ece department</title>
    </head>
    <center><img src = "/static/images/ece.png" height="250" width="600" align="center"></center>
    <h3 align="center">ECE department</h3>
	<body>
		<p> 
 
The Department was established in 1970 with B.E. programme in Electronics and Communication Engineering. Later on, in 1981 post graduate programme in M.E. Applied Electronics and in 2003 M.E. VLSI Design programme were also started in the Department. All the courses are offered as both part-time and full-time. 
 
The Department has total staff strength of 16 including Teaching and Non-Teaching staff. The experienced professors guide the Department aiming at educating and training students with sound knowledge and awareness in the fields of electronics, communication and information technology. 
 
The Department is recognized for research under Information and Communication Engineering affiliated to Anna University::Chennai. The Department has signed MoU with several companies like Texas Instruments, Robert Bosch which provide training to faculty and students on recent techniques.Various workshops and trainingprogrammeare frequently conducted in the Department. Every year Department organizes National conference on Advanced Computing and Communication Systems. A National level technical symposium ‘NEXUS’ is being conducted by ECE students association. 
</p>
	</body>
</html>
#mech.html:
<!DOCTYPE html>
<html>
	<head>
		<title>mechanical department</title>
    </head>
    <center><img src = "/static/images/mech.png" height="250" width="600"></center>
    <h3 align="center">Mechanical department</h3>
	<body>
		<p>The Government College of Technology formerly named as Arthur Hope College of Technology, was established in July 1945 to provide valuable guide ship to the industrial sectors in variant field of manufacturing. In this reputed institution, the Department of Mechanical Engineering geared up in the academic year of 1952 with the Undergraduate Programme and in the year 1971 Engineering Design as a Post Graduate Programme continued by Manufacturing Engineering in the year 1980 and Thermal Engineering in the year 2002. The involvement and contribution of work force on teaching and learning process of both teaching and non-teaching staff enrich the Mechanical Department of as a pioneer one. Coimbatore is the Manchester of South India' having Foundries, Textile machinery manufacturing industries, Automobile spares manufacturing industries. Also it is runner to full-fill the need of globalized engineering requirements. To the industrial needs and to stabilise their logo in the field, man-potential with in-hands training knowledge in mechanical engineering is important. The department has been showing in-hands training knowledge to their mechanical discipliners with the aid of conventional and modernized technology systems. The department has achieved NBA with its academic records and supporting activities to the industries. The modern technology of CMM, CNC Machineries, Wire cut EDM, Advanced Thermal Measurement Techniques, Vibration Fundamental Trainer, 3D Printing and Advanced Casting Technologies have been included in the curriculum to build up the students as a handsome engineer to the modern technological fields. To elevate the discipliners as an entrepreneur in its specialization of field, the industrial environment training programmes passionate with the academic topics. Measurement on every carrier creates a novelty in their life style in the engineering environment.  
 
 
</p>
	</body>
</html>
#caddlab.html:
<!DOCTYPE html>
<html>
	<head>
		<title>Cadd lab</title>
	</head>
	<body>
         <center> <img src = "/static/images/cad.jpg" align="center" height="300" width="800"></center>
        <h3 align=center>ACCET CADD LAB</h3>
		<p>             
Computer-aided design (CAD) is the use of computers (or workstations) to aid in the creation, modification, analysis, or optimization of a design.[1] This software is used to increase the productivity of the designer, improve the quality of design, improve communications through documentation, and to create a database for manufacturing.[2] Designs made through CAD software are helpful in protecting products and inventions when used in patent applications. CAD output is often in the form of electronic files for print, machining, or other manufacturing operations. The terms computer-aided drafting (CAD) and computer aided design and drafting (CADD) are also used.[3] 
 
Its use in designing electronic systems is known as electronic design automation (EDA). In mechanical design it is known as mechanical design automation (MDA), which includes the process of creating a technical drawing with the use of computer software.[4] 
 
CAD software for mechanical design uses either vector-based graphics to depict the objects of traditional drafting, or may also produce raster graphics showing the overall appearance of designed objects. However, it involves more than just shapes. As in the manual drafting of technical and engineering drawings, the output of CAD must convey information, such as materials, processes, dimensions, and tolerances, according to application-specific conventions. 
 
CAD may be used to design curves and figures in two-dimensional (2D) space; or curves, surfaces, and solids in three-dimensional (3D) space.[5][6]: 71, 106  
 
CAD is an important industrial art extensively used in many applications, including automotive, shipbuilding, and aerospace industries, industrial and architectural design (building information modeling), prosthetics, and many more. CAD is also widely used to produce computer animation for special effects in movies, advertising and technical manuals, often called DCC digital content creation. The modern ubiquity and power of computers means that even perfume bottles and shampoo dispensers are designed using techniques unheard of by engineers of the 1960s. Because of its enormous economic importance, CAD has been a major driving force for research in computational geometry, computer graphics (both hardware and software), and discrete differential geometry.[7] </p>
	</body>
</html>
#lib.html:
<!DOCTYPE html>
<html>
	<head>
		<title>Codebeautify.org Text to HTML Converter</title>
    </head>
    <center><img src = "/static/images/lib.jpg" height="300" width="600" align="center"></center>
	<body>
        <h3 align="center">Library</h3>
		<p>A library is a collection of materials, books or media that are accessible for use and not just for display purposes. A library provides physical (hard copies) or digital access (soft copies) materials, and may be a physical location or a virtual space, or both. A library's collection can include printed materials and other physical resources in many formats such as DVD, CD and cassette as well as access to information, music or other content held on bibliographic databases. 
 
A library, which may vary widely in size, may be organized for use and maintained by a public body such as a government; an institution such as a school or museum; a corporation; or a private individual. In addition to providing materials, libraries also provide the services of librarians who are trained and experts at finding, selecting, circulating and organizing information and at interpreting information needs, navigating and analyzing very large amounts of information with a variety of resources. 
 
Library buildings often provide quiet areas for studying, as well as common areas for group study and collaboration, and may provide public facilities for access to their electronic resources; for instance: computers and access to the Internet. The library's clientele and services offered vary depending on its type: users of a public library have different needs from those of a special library or academic library, for example. Libraries may also be community hubs, where programs are delivered and people engage in lifelong learning. Modern libraries extend their services beyond the physical walls of a building by providing material accessible by electronic means, including from home via the Internet. 
 
The services that libraries offer are variously described as library services, information services, or the combination "library and information services", although different institutions and sources define such terminology differently. </p>
	</body>
</html>
```
## Output:

## Result:
mapping program was executed successfully
