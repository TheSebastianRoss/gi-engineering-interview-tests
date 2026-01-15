
# Documentation
This file documents notes and requested recommendations for the different tasks involved in this interview assessment project.

## Task 1: 
Create an accounts controller with list, create, read, update and delete endpoints.
	- UID of locations was not an element in the LocationDto. Accounts are associated to locations by the location's UID. This causes an issue when creating a new account, as the location's UID is required but can't be easily accessed. Added UID as a field in the LocationDto class as a workaround.
	- It is unclear what the accounts PendCancel field is or how it's used.
	- Similarly, it's not entirely clear whether or not the accounts Status field is supposed to be AccountStatusType (since that type is also used for locations), but I made what I felt was a reasonable assumption.

