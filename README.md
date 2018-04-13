# our-repository1
In revision control systems, a repository, is an on-disk data structure which stores metadata for a set of files or directory structure. Depending on whether the version control system in use is distributed (for instance, Git or Mercurial) or centralized (Subversion or Perforce, for example), the whole set of information in the repository may be duplicated on every user's system or may be maintained on a single server. Some of the metadata that a repository contains includes, among other things:

A historical record of changes in the repository.
A set of commit objects.
A set of references to commit objects, called heads.

Storing changes
The main purpose of a repository is to store a set of files, as well as the history of changes made to those files.[2] Exactly how each revision control system handles storing those changes, however, differs greatly: for instance, Subversion has in the past relied on a database instance and has since moved to storing its changes directly on the filesystem. These differences in methodology have generally led to diverse uses of revision control by different groups, depending on their needs.
