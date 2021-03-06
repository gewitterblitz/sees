Exercises
=========

1. ``clone`` the repository from http://fossee.in:9000 into a directory
   called sees. You should see a folder ``punchagan`` with a lone directory
   ``01-mercurial`` inside that. The ``log`` should show you the lone commit
   of the repository. 

#. The next step is to create a folder for yourself inside the repository.
   The idea is to create a central repository for the course, where every
   participants files are put in his own folder (within a chapter
   sub-folder). You are expected to commit future class-work to this
   repository. 

   Before beginning this exercise, set your username in you global ``hgrc`` 

#. Create a new sub-folder (at the same level as ``punchagan`` with your
   name.) Add ``01-mercurial`` as a sub-folder to it. Copy the
   ``questions.txt`` from ``punchagan/01-mercurial`` to
   ``<your-name>/01-mercurial``. Now, commit your changes with a meaningful
   commit message and ``push`` . If ``push`` fails, ``pull`` , ``merge``,
   ``commit`` and then ``push``.

#. Pull from the repo. Update. Use ``hg log`` to see the log history of the
   repository.

#. Answer the questions in ``questions.txt``. Commit your changes with a
   meaningful commit message and push them. (If required, ``pull`` ,
   ``merge``, ``commit`` and then ``push``)

#. Wait for your neighbor to finish making his/her changes. Help him/her if
   required. Once both of you are ready, pull changes from the repository and
   update. 

   Now, add one question each, at the bottom of your own ``questions.txt``
   file and your neighbor's file. Preferably, the questions should be about
   ``hg`` , but you may, let your creativity run wild. ;) Commit the changes
   and push them. Resolve merge conflicts, as required.

#. Answer the new questions that were added by your neighbor, both to his/her
   file and your file. Commit changes. Push.

#. Edit the file ``people.txt`` in ``punchagan/01-mercurial`` . Add your
   name, followed by a colon, followed by a comma separated list of your
   interests. Commit your changes and push.

#. Edit the file ``story.txt`` in the folder ``punchagan/01-mercurial`` and
   add one sentence at the end of the present story. Commit your changes and
   push them. Wait until at least 3 other people change the file, before you
   make your next change. This can continue for as long as you like. ;)

.. 
   Local Variables:
   mode: rst
   indent-tabs-mode: nil
   sentence-end-double-space: nil
   fill-column: 77
   End:

