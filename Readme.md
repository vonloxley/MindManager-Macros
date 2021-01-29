# MindManager Macros

Macros for MindManager (MM) that ease (some) of the pains of planning projects
with MM.

## MakeAllSelectedDependentOnFirstSelected.mmbas
Standard behaviour of MM is chaining all tasks. This macro will make all tasks
depend on the first selected task.

## RemoveAllRelationships.mmbas
Remove all realtionships this task is part of. This macro demonstrates the usage
of transactions in MM-macros.

## RemoveAllRelationsIfNameIsEqual.mmbas
Remove all realtionships this task is part of but only if both parts of the 
relation have the same name.

## SetDurationToMultipleOfAufwand.mmbas
This macro calculates the duration of a task based on its effort using a
divisor. If you planned with one full-time equivalent, but find out that
only three quarters are available for the task, you put in 0.75. Do not forget
to decouple effort and duration before using this macro.
