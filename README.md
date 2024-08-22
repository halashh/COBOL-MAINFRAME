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


