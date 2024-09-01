# COBOL-MAINFRAME

Personal Notes:

Computer architecture:
Components:
-Instructor Set Procedure.
-Datapath and Control.
-Digital Design.
-Circuit Design.
-Physical Design.

In mainframe de aux storage o OWC is in DASD (Direct Access Storage Device) the last mention are HardDisk or SolidDisk.

OS:
Status:
-NEW: process is in building stage.
-READY: its ready, but the CPU its busy execution any else.
-RUNNIG: in process. Executing.
-WAIT: depends on another action to be executed.
-TERMINATED: the actions/executions was ends.

OS functions:
1. Process Management
2. Security Management
3. File Management
4. Communications Management
5. Resource Management
6. Memory Management

Mainframe Operating Systems:
-z/OS: It can execute many types of jobs/tasks on the same time.

-Z/TPF: Use in companies that needs execute transactions in real time.

-z/VM: Its a virtual workspace, necessary to develop and test.

-z/VSE: Its a copy of z/OS but with less resources than z/OS.

-Linux on IBM Z: Using on phones, console videogames, watches, etc.

-KVM on Z: Hipervisor opensource.

Process:
![image](https://github.com/user-attachments/assets/e0d2388c-dfac-4873-99db-d7798b6cb7de)



Which operating system function makes sure all of the running programs and processes on the system play well with one another?
-Resource Management

What is the best statement regarding computer architecture
-It is the set of rules and methods that describe the functionality, organization, and implementation of the computer system

Which process management state describes a process being created?
-New


Which operating system option provides interactive time sharing from remote terminals?
-TSO (Time sharing option)


Select the correct statement regarding application software
-Runs on top of the operating system

Which IBM transaction processing monitor provides rapid high-volume transaction processing?
-CICS (Customer information control system)

Mainframe memory is also referred to as:
-Storage


IBM Z Configuration Setup:
[IBM.pdf](https://github.com/user-attachments/files/16711659/IBM.pdf)


Glorssary:
[Glosary Terms IBM.pdf](https://github.com/user-attachments/files/16714258/Glosary.Terms.IBM.pdf)



Which of the following provides the ability to allow users on multiple systems to access data sets on shared DASD volumes?
The correct answer is: GRS


W​hat might a typical IBM Z Mainframe environment consolidate?
The correct answers are: Power Supplies, CPU, Cooling, Network Adapters

Which mainframe component syncs the time of day between multiple servers?
The correct answer is: Server time protocol

What is the maximum number of z/OS images in a Parallel Sysplex environment?
The correct answer is: 32

W​hat's an example of a batch process?
The correct answer is: Payroll

Security Mainframe:
![image](https://github.com/user-attachments/assets/622f2ac5-945a-476c-b914-8671c2bf883f)

![image](https://github.com/user-attachments/assets/4061f25c-727f-40b0-8f3c-7adb8aad997b)

Transaction Level Security:
It consists of encrypting the information and only whoever has the key can decrypt it.
It can be encrypted with a public key and can only be decrypted with a private key.



Where are the IOCDs’ stored?
The correct answer is: Support elements

Which mainframe hardware component is located on the processor for Symmetric key functions?
The correct answer is: CPACF

What are the three main objectives of system security?
The correct answer is: Confidentiality, integrity, and availability

W​hat's the initial security request flow for a user request assuming RACF?
The correct answer is: U​ser request-> Resource Manager-> SAF-> RACF->RACF Database

Which IOCDS statement is used to define the FICON switch address?
The correct answer is: CHPID

Which system component decides the allocation of system resources?
The correct answer is: Resource Manager

What type of cryptography uses a pair of key values rather than a single key?
The correct answer is: Public Key

The Load Parameter consists of 8 positions. What is indicated in the first 4 positions?
The correct answer is: IODF device number

What would be the reason to place a key into storage?
The correct answer is: Better performance

Which device contains the IPL loadable code?
The correct answer is: SYSRES


QUIZ:
1. ¿Cuál de las siguientes opciones proporciona la capacidad de permitir que los usuarios de múltiples sistemas accedan a conjuntos de datos en volúmenes DASD compartidos?
b. XCF

2. ¿Qué opción del sistema operativo proporciona una compartición interactiva de tiempo desde terminales remotos?
a. TSO (Time sharing option)

3. ¿Cuál de los monitores de procesamiento de transacciones de IBM proporciona procesamiento rápido de alta capacidad?
d. CICS (Customer Information Control System)

4. La memoria de mainframe también se conoce como:
b. Storage

5. ¿Cuál es el componente del sistema z/OS que gestiona la comunicación entre aplicaciones en un Parallel Sysplex?
b. Cross-System Coupling Facility (XCF)

6. ¿Qué función del sistema operativo asegura que todos los programas y procesos en el sistema interactúen correctamente entre sí?
d. Resource Management

7. ¿Qué tipo de criptografía utiliza un par de claves, una pública y una privada?
b. Public Key

8. ¿Qué archivo o conjunto de datos se utiliza durante un IPL y contiene las definiciones de hardware y software del sistema?
d. IODF

9. ¿Cuál es el estado del proceso de administración cuando un proceso está esperando que el procesador maneje la solicitud?
a. Ready

10. ¿Qué permite que los datos se descifren en el momento en que se necesitan?
b. Pervasive encryption

11. ¿Cuál es el nombre del dispositivo que contiene el código de carga inicial (IPL)?
b. SYSRES

12. ¿Cuál es el nombre del motor criptográfico de alto rendimiento que existe para cada procesador IBM Z?
c. CPACF

13. ¿Cuál de las siguientes declaraciones IOCP es opcional?
c. All of these options

14. ¿Qué significa GDPS?
a. Geographically Dispersed Parallel Sysplex

15. ¿Qué proporciona un conjunto común de métodos para realizar funciones que el sistema operativo utilizará?
a. Firmware

16. ¿Qué posiciones en el Load Parameter contienen la información sobre los mensajes que se mostrarán durante el IPL?
b. 7

17. ¿Qué componente de z/OS se usa para gestionar la distribución de carga de trabajo, el balanceo de carga de trabajo y la distribución de recursos a las cargas de trabajo en competencia?
c. Workload Manager

18. En el escenario en el que todos los 85 LPARs están IPL’ed, ¿qué perfil de activación, al ser activado, hará que todos los LPARs y sus sistemas operativos se caigan?
b. Reset

19. ¿Cuál es la definición más precisa de un espacio de direcciones?
d. Appears to exist as main storage, although most of it is held in secondary storage

20. ¿Cuál es la definición principal de LDAP?
c. Defines a standard method to access and update information in a directory.

21. Las aplicaciones que se ejecutan en un sistema operativo a través de una serie simplificada de interfaces se denominan:
True

22. ¿Qué software permite el funcionamiento del hardware en un mainframe?
b. LIC (Licensed Internal Code)

23. La arquitectura se compone de:
a. Software and Hardware

24. ¿Cuál es el procesador caracterizado que ejecuta comandos en un mainframe?
b. CP (Central Processor)

25. ¿Cuál es la definición más precisa de una tarjeta de interfaz de red (NIC)?
d. A NIC is a computer hardware component that connects a computer to a network.

26. ¿Qué palabra clave del CNTLUNIT especifica la dirección o direcciones a las que está conectado el control unit?
d. Link address

27. En TSO/ISPF, ¿cuál es el nombre de un conjunto de datos que contiene múltiples miembros, cada uno de los cuales contiene un sub-conjunto de datos?
b. Partitioned data set

28. ¿Qué término se utiliza cuando el sistema operativo mueve datos desde el almacenamiento auxiliar a la memoria central?
b. Retrieving

29. ¿Qué declaración define los LPARs y los subsistemas de canal lógico?
d. Resource

30. ¿Cuál es el número mínimo de LPARs en un Sysplex?

b. 1

Introduction to TSO and ISPF

TSO: Time Share Options
ISPF: Interactive System Productivity Facility

![TSO](https://github.com/user-attachments/assets/432f8af8-c8a7-440e-aa47-fed037175469)

Ingresar S en el espacio anterior a cada opción y presionar enter para continuar:
Ejemplo:
s -Nomail

-Nomail: TSO suprimira el mensaje de para mi usuario durante el inicio de sesión.
-Nonotice: No quiero ver mensajes destinados a ninguno de los usuarios.
-Reconnect: Reconectara a una sesión cerrada accidentalmente.
-OIDCard: Para introducir datos con tarjeta de operador.

ISPF:
![image](https://github.com/user-attachments/assets/9a290202-9ac3-4f77-9df9-56a626d929a2)

ISPF Commands:
![image](https://github.com/user-attachments/assets/75dea001-f175-4737-bccf-6529cda148ea)

Log Data Set Disposition
ISPF maintains a log of significant user activities. This information can be useful, for example,
when diagnosing problems. The log data is stored in a data set named userid.SPFLOGx.LIST,
where userid is your TSO user ID. 
At the end of an ISPF session you, as the user, can specify what has to be done with the log data
set. Enter the selection of your choice.
Print data set and delete: Prints the data set, then deletes it. You must specify an output class or a
local printer ID. If you specify an output class, ISPF submits a background job to print and delete
the data set. If you specify a local printer ID, ISPF uses TSO's PRINTDS command to route the
data set to the printer and then deletes the data set.
Delete data set without printing: Just deletes the data set.
Keep data set - Same: This option closes and frees the data set and allocates the same data set in
the next session.
Keep data set - New: This option closes and frees the data set but allocates a new data set when
starting the next ISPF session.
Delete data set without printing or Keep data set - Same is the usual choice unless you have had
problems.
If you do want to print, then the printer class (SYSOUT class) or destination (local printer ID) must
be entered.
Additionally, the four lines of Job statement information must be entered if you use the SYSOUT
option.
The line List Data Set Options not available indicates there is no list data set to print.
If we performed a print under ISPF, then a similar set of options are provided to dispose of the list
data set.

Just to clarify some z/OS terminology:
 • In this lab, when you read “allocate a new data set”, it means what other systems call
“create a file”. It is true that “data sets” are not the same as files, but, for the type of data
sets we’ll be working with, it’s OK to think of them as files.
 • A PDS (Partitioned Data Set) is a file that contains other files called “members”. This is
similar to a PC folder that contains files (with one difference: a PC folder may contain
sub-folders. A PDS can only contain members, that is, files).
 • A PDSE (PDS Extended) is a newer version of PDS. They are easier to maintain and manage,
but it is unlikely that you’ll notice a difference. You will normally work with PDSEs.
 • A sequential data set, or sequential file, is just that, a file. Members inside a PDS or PDSE are
sequential data sets. They are called “sequential” because you read them (or write them) one
record at a time, starting from the first record, then the second, and so on, sequentially.

Traducción:
Sólo para aclarar algo de terminología de z/OS:
 • En esta práctica de laboratorio, cuando lee “asignar un nuevo conjunto de datos”, significa lo que otros sistemas llaman
“crear un archivo”. Es cierto que “conjuntos de datos” no son lo mismo que archivos, pero, por el tipo de datos
conjuntos con los que trabajaremos, está bien pensar en ellos como archivos.
 • Un PDS (Conjunto de datos particionados) es un archivo que contiene otros archivos llamados “miembros”. Esto es
similar a una carpeta de PC que contiene archivos (con una diferencia: una carpeta de PC puede contener
subcarpetas. Un PDS sólo puede contener miembros, es decir, archivos).
 • Un PDSE (PDS Extended) es una versión más nueva de PDS. Son más fáciles de mantener y gestionar,
pero es poco probable que notes una diferencia. Normalmente trabajará con PDSE.
 • Un conjunto de datos secuenciales, o un archivo secuencial, es sólo eso, un archivo. Los miembros dentro de un PDS o PDSE son
conjuntos de datos secuenciales. Se llaman “secuenciales” porque los lees (o los escribes) uno
registro a la vez, comenzando por el primer registro, luego el segundo, y así sucesivamente, secuencialmente.

Allocate data set especification:
Give the new data set the following specifications:
a. We’ll tell the system how much space the new data set will take, in units of disk tracks
Enter trks in Space units (see screenshot below).
b. Two tracks primary space: the data set occupies 2 disk tracks initially.
Enter 2 in Primary quantity.
c. One track secondary space: if the data grows and more tracks are needed, the data set
grows 1 track at a time.
Enter 1 in Secondary quantity.
d. Fixed Blocked length records. All the record have the same size.
Enter FB in Record format.
e. Record length 80 bytes.
Enter 80 in Record length.

![image](https://github.com/user-attachments/assets/192f3283-9a84-40d4-a8ba-4a04d6552025)

Allocate a Partiotined Data Set (PDS):
. At the Allocate New Data Set panel, enter the following specifications for the data set
(note the panel is filled with the values from the last data set you allocated):
a. Space units: BLKS.
b. Ten blocks primary space. Note this time space units is blocks (BLKS), not tracks (TRKS)
c. Five blocks secondary space.
d. Directory size two blocks. This is what makes the data set a PDS: the fact that it contains
a directory (think of it of an index, or catalog, of the members inside the PDS)
e. Variable length records. Individual records inside each member have different sizes, up
to the size specified in Record length (255, see below).
f. Blocked records. When reading or writing, the system reads or writes many records
placed together in a single block.
Enter VB in Record format to specify Variable-length, blocked records.
g. Block size determined by system. Leave the Block size field blank, or enter 0 (zero).
h. Record length 255 bytes.

After typing in all the values, press Enter. The data set is allocated.
__ 16. To verify whether the data set has been allocated properly, use the Data Set information
panel. Press Enter again after allocating the data set. You should see:
Note the Organization is PO: Partitioned Organization (this means PDS).
1st Extent (12 blocks) is the initial space allocation. It consists of the Primary quantity (10
blocks) and Directory blocks (2).
If a block size is not specified for the creation of a data set, the system attempts to
determine the block size.
Using a system-determined block size has the following benefits:
 - The program can write to DASD, tape, or SYSOUT without you or the program
calculating the optimal block size. DASD track capacity calculations are complicated.
Optimal block sizes differ for various models of DASD and tape.
 - If the data set is later moved to a different DASD type, such as by DFSMShsm, the
system recalculates an appropriate block size and re-blocks the data.

Exercise:
![image](https://github.com/user-attachments/assets/149a8f0b-8192-4d8f-a8fb-f9e8364befe0)


Allocate a Partitioned Data Set Extended:
So, given that both contain members, what is the difference between PDS and PDSE?
When you create a PDS, you specify disk space in two parts: how big is the data set (in tracks,
blocks, cylinders...) and how big is the directory inside the dataset. For example a data set can
occupy 50 tracks on disk, and 2 of those are the directory. The problem with PDS was that you had
to watch 2 resources that could fill up: if your members are too big, they may need more than 50
tracks, and you would end up with a “no more space for data set” situation. If you create too many
members in the PDS, you could have a “no more directory space” error.
When a PDS member is updated, it is written at the end of the PDS, and there remains a “hole”
where the old version was. Same when a member is deleted: it is removed from the directory, but
still occupies its original space on disk. Over time, the PDS starts to look like a Swiss cheese: full
of holes. Eventually, the PDS can run out of space. To prevent that, system administrators must
run the Compress utility periodically.
With PDSE, the directory still exists, but it is managed automatically by the system. You never
have to worry about running out of directory space, or having to run the Compress utility. As you
saw, you don’t even have to specify a directory size when creating a PDSE.


Create a PDS member:
In the previous exercise, you created a Partitioned Data Set (PDS) named
userid.ES10.PDS. The userid is the user ID you used to log on to TSO with.
__ 1. From the ISPF Primary Option Menu, access the Edit Entry Panel by entering 2 (Edit) on
the command line (remember to press Enter after typing in 2):
__ 2. The Edit Entry Panel will open. Ensure that the partitioned data set you created in the
previous exercise is in the ISPF Library:
If the data set under ISPF Library is not the PDS you created earlier, make the necessary
changes:
If Project doesn’t show your TSO userid, press Tab until you get to Project and enter your
TSO userid. Not TSOCA23, that’s just an example.
If you pressed Tab too many times and skipped the field you wanted, use SHIFT + Tab to
go back, or keep pressing Tab until the cursor wraps round and lands under the field.
V12.0
EXempty
Exercise 3. ISPF editor primary commands
Course materials may not be reproduced in whole or in part without the prior written permission of IBM.
© Copyright IBM Corp. 2019, 2024 3-3
If Group doesn’t contain ES10, press Tab until the cursor is next to Group and enter ES10.
If Type doesn’t contain PDS, press Tab until the cursor is next to Type and enter PDS.
__ 3. Create a member named LITLGAME. Press Tab until the cursor is next to Member and
enter LITLGAME, then press Enter.


Edit the LITLGAME member:
![image](https://github.com/user-attachments/assets/c8669962-bb94-4a2c-ab42-7df3d1c27078)

X ALL: Hide the lines with code.
RESET: Show the hide code.
BNDS: Write bnds in a number line to change a char value. Then in lines command write " C (chars to change) (char you want to change to) "

That’s interesting, excluding all lines. Sounds like a good party trick. What is it for?
Well, the FIND and CHANGE commands have the option of operating on excluded or
non-excluded lines, giving you better control over what to find or change.
If there is a section of code in a program that you don’t want to change, you can exclude that
section and then use C XXX YYY NX ALL (change all non-excluded instances of XXX to YYY).

F: Use F to find a char in the code.
RFIND (REPEAT FIND): Use RFIND to research a char in the code.

Scrpit en REXX (Lenguaje para automatización):
/*THIS IS A LITTLE REXX-EXEC*/
ANSWER ='Y'
DO WHILE ANSWER='Y'
GUESSNUMBER=1
 NUMBER=RANDOM(1,50)
 SAY "Let's play a little game. I think of a number between"
 SAY "1 and 50 and you have to guess it!"
 say "OK, I picked a number."
 DO UNTIL NUMBER=GUESS
 SAY "Enter guess #"GUESSNUMBER;PULL GUESS
 IF GUESS>NUMBER THEN SAY "Too big!"
 IF GUESS<NUMBER THEN SAY "Too small!"
 GUESSNUMBER=GUESSNUMBER+1
 END
 SAY "You are right, my number is" NUMBER
 SAY "Would you like to play another game? (Y/N)";PULL ANSWER
END


