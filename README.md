# Consolidation
Identify and merge / versioning of similar files

Usage
=====
In crash or every days saving/cleaning routine:
   Saving/recovering datas, files, documents, code, projects for any content types.
   
Features
========
Make a save on a external memory: 
   Identify identical and similar documents. 
   Make a report.
   Save documents in the merge arborescence:
      * identical are saved only once
      * similar are saved with 1 most common + "patchs" (git patchs)
      * they are compressed
   Make a dated fake symbolic arborescence description, to get back the original one on the pc.
   
   Recurent save: 
      * check/keep/make diff existing files in the merge arborescence. 
      * check/keep/make diff of existing arborescence description. 
   
   Have a rollback script for every saving dated event.
   Check every rollback.
   Have a cleanner script that will remove or merge identified similar files + Report.
   Have a listed generated directories or generated files, plus a script of build + verification.
   Have a database dump / rollback step.
   Have a testing set to test full rollback:
        arbo reconstruction
        regeneration of databases
        rebuild of generated files
        testing scripts
   Generate a rolback report.
