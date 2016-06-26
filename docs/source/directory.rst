.. _directory_structure:
Directory Structure
===================

The experiment consists of the following files and directories::

  Pictures                 : directory containing images used in phase 3
  itemlist_<name>.txt      : item list files
  phase1_pre-rating.ebs2   : runnable file for phase 1
  phase1_pre-rating.es2    : source file for phase 1
  phase2_assignment.ebs2   : runnable file for phase 2
  phase2_assignment.es2    : source file for phase 2
  phase3_report.ebs2       : runnable file for phase 3
  phase3_report.es2        : source file for phase 3
  phase4_post-rating.ebs2  : runnable file for phase 4
  phase4_post-rating.es2   : source file for phase 4
  resting_state.ebs2       : runnable file for resting state phase
  resting_state.es2        : source file for resting state phase


Subject specific directory
--------------------------
The experiment creates a sub-directory in the experiment directory for each
subject. The directory name reflects the subject number and the session number
(usually 1).

Example::

  subject_<subject number>_session_1

:Attention:
  In order to achieve correct data all phases must write the data for a subject
  into the same sub-directory. It is important that the same subject and
  session numbers are set at the beginning of each pahse. Also note that the
  session number should always be 1 (the session number does NOT reflect the
  phase in the experiment).
