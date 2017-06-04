Data Tables
===========


Item List Table
---------------
The item list data table is also writte as a CSV file to the subject specific
directory. The semantics of the columns is explained below:

UID
  Unique identification number of the item list
Name
  Name of the item list (extracted from the filename)
ItemCnt
  Number of items in the item list
DiscardedCnt
  Number of items in this list that have been discarded after the first rating


Item Table
----------
The item data table is also writte as a CSV file to the subject specific
directory. The semantics of the columns is explained below:

UID
  Unique identification number of the item
Task
  Task text
ListID
  Identification number of the list the item belongs to
Block
  -1: Item was discarded after the first rating
  1: Item was presented in the first report block
  2: Item was presented in the second report block
RatingBefore
  Rating value acquired in phase 1
RatingAfter
  Rating value aqcuried in pahse 4
ChoiceTrial
  Number of self-choice trial in which the item was presented (trial numbers start with 1)
AssignmentTrial
  Number of assignment trial in which the item was presented (trial numbers start with 1)
PositionChoice
  Position in which the item was presented in the self-choice trial (1:left, 2:middle, 3:right)
PositionAssignment
  Position in which the item was presented in the assignment trial (1:left, 2:middle, 3:right)
SelfAssigned
  Number of self-choice trial in which the item was chosen (0 if item was never chosen)
OtherAssigned
  Number of assignment trial in which the item was assigned (0 if the item was never assigned)
ReportedSelf1
  0: time limit in report block 1 exceeded
  <0: -1 * number of the trial in report block 1 in which the item was reported as self chosen
  >0: number of the trial in report block 1 in which the item was reported as not self chosen
ReportedOther1
  0: time limit in report block 1 exceeded
  <0: -1 * number of the trial in report block 1 in which the item was reported as assigned
  >0: number of the trial in report block 1 in which the item was reported as not assigned
ReportedSelf2
  0: time limit in report block 2 exceeded
  <0: -1 * number of the trial in report block 2 in which the item was reported as self chosen
  >0: number of the trial in report block 2 in which the item was reported as not self chosen
ReportedOther2
  0: time limit in report block 2 exceeded
  <0: -1 * number of the trial in report block 2 in which the item was reported as assigned
  >0: number of the trial in report block 2 in which the item was reported as not assigned
