<h4>Relationships</h4>

* One to Many: Most Common
* One to One: Not very Common
* Many to Many: Not Ideal, but Common
    > A joining table is used to achieve this.
* Self Relationship: Table joins to itself.


<h3>Second Normal Form</h3>

* Second stage of the Normalisation Process: Fulfill the requirements of 1NF and Each non-key attribute must be functionally dependent of PK.
* Non-key attribute: Attribute i.e not PK.
* Functionally Dependent: Attribute determined by PK.
* FK: Used to link 2 tables. Related to PK of another table.

<h3>Third Normal Form</h3>
 
* Fulfill 2NF and have no transitive dependency.
* Transitive dependency: Every non-key attribute must be dependent on the PK and PK only.

<h3>Datatypes</h3>

* Each field needs a datatype.
* Should be same no matter what DBMS are we using.
* Many types have additional info.
    > Size or length.
    >
    > Precision.
* Choose types wisely as they are hard to change later. They need to be efficient and long enough to handle large situations.

<h3>Integrity Constraints</h3>

* Feature that can be set while designing tables.
* Enforces data integrity and ensures data is complete and accurate.
* Eg: Null, Not Null, Ranges
* Helps improve data quality in DB.
* Should reflect our requirements.

<h3>Lookup Table</h3>

* Also called Reference table.
* Data that is used by the system.
* Usually a standalone table.
* Ensure information is kept separate from any systems using it.

<h3>Auditing Table</h3>

* Keep a history of changes to a table.
* Database logic or application.