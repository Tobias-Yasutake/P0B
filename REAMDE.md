# Project-0
Project 0 B includes a demonstration of Custom Objects needed for a sample mail system, called POSTAL SERVICE
It also includes an example of apex code needed for functionality that cannot be achieved declaratively.

Mail status can be updated by a driver.
Routes can assigned by a mail handler.
Neither the driver nor the mail handler can edit anything other than their specific field on the mail object.
Insured lost mail needs approval from a superior before it can be marked as lost.
Flows and Workflows are used to ensure that every contact has an account.
APEX functions call SOQL quereies as to do quick updates that would be difficult to do delaritvely
(in this case, modify all accounts in California, as we no longer do business in CA)
