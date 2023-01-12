## MKS Reliability Engineering WorkSpace
 The main use for this repository is efforts for automation in reliability testing and procedures. Projects may be exclusively software, exclusively hardware, or a mix of both. Projects created must be associated with reliability testing and procedures. 
 
### Software 
  Major changes to software must be presented in a new version. Major changes would include--and is not limited to--library additions change, new code structure, addition, removal of two or more large physical components (i.e. eliminating DMMs from the communication procedure), hardware change (i.e. different IC pinout).  
  
### Hardware
  Should a project contain hardware, the files for hardware design (KiCAD, PADs, etc.) should be contained in a folder in the same repository as the sofware that goes into it. Major changes in hardware must be presented in a new version. Major changes would include--but are not limited to--IC swaps, connector swaps, layout change, THT --> SMT (or vice versa). Changing passive components (resistors/capacitors/inductors) can be considered a minor change.   

### Project Nomenclature
  Repositories are to be created according to 5 prefixes: 
  +Component        [COM]: Project used exclusively for component testing.
  +Sub Assembly     [SUB]: Project used exclusively for Sub Assembly Testing.
  +Generator        [GEN]: Project used for Generators/Life Test. 
  +Lab Equipment    [LAB]: Project used for or in conjunction with lab equipment.
  +Fixture          [FIX]: Project is miscellaneous or can be used in various different places.
  
  After prefixes, initials should be placed and a breif title for the project. 
  After the title the version must be presented. 
  
  For Example: 
  >LAB-AT-LAMBDA_CONNECTOR-V0.0.0
  
  **Version Nomenclature**
  The version is subdivided into three sections project creation and modification MUST adhere to these rules.
  + The First Digit indicates the overall project version. A project that has undergone 4 project changes (with no hardware or software changes) would read...
  >V4.0.0
   
   Every project should start with a 1 in the first digit unless it is an exclusive software or exclusive hardware project. In this case, the first digit would read a zero.
  
  + The Second Digit indicates the software version. A new project that has undergone 3 major software changes (with no hardware changes) would read... 
  >V1.3.0
  
  + The Third Digit indicates the hardware version. A new project that has undergone 3 major hardware changes (with no software changes) would read...
  >V1.0.3
  
  **Repositories**
  New repos should ONLY be created for a new version of a project. Software and hardware revisions for a project should be contained in the same project version. If a project is exclusively hardware or exclusively software, the revisions are to be contained in the same repository unless the project is altered in a manner that changes the function of the project. 
  
### Project Information
  The README for each project should contain the following: 
  +Brief description of Project
  +Language used (along with version IF applicable. i.e. Python 3.7)
  +Program Used to upload/debug w/ version (IF applicable i.e. Arduino 18.0.1 or Eclipse 1.1)
  +Hardware Program w/ version (IF applicable i.e. KiCAD 6.0)
  +Operation (IF applicable i.e. How to use device)
  +Other relevant information (i.e. Command Lists, Configurations, Compatibility)
