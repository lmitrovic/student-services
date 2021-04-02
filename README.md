This project simulates a student service application. The whole model consists of more than 20 entities. Student actions are supported: exam registration, taking the exam, course of study, enrollment of the year, renewal of the year, etc. There is an entity school year in the system, of which one school year is always active. One teacher teaches several subjects in one school year. One subject can be taught by several teachers. A student in the school year listens to subjects with certain teachers, each subject with one teacher. Each functionality should communicate with the ORM layer which is realized through the layered architecture. The architecture consists of an FXML controller, a service, and a CRUD repository. The last part of the implementation of the software for the student service is the implementation of the import of data from the CSV file and the creation of reports. The build tool Maven and Hibernate ORM were used in the implementation.