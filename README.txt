// $Id: $

Circulation
-----------

Circulation is a small module which facilitates the signing in and out of library materials catalogued in a Drupal system.

Premises:

1) You have one or more content types containing bibliographic info for library materials.
2) You have a single content type used to represent individual copies of borrowable media.
3) Your library accounts equal drupal accounts.  
  Might actually make sense to include a permission: can borrow.


This module was built to support the the lending of zines at the Anchor Archive Regional Zine Project (a zine library in Halifax, NS).


Installation
------------

1.  Copy the module to your <site>/modules directory and enable as usual.
2.  Visit your permissions page and set 'access circulation' and 'administer circulation' permissions.
3.  Before you're able to use the module you'll need to visit admin/settings/circulation and:
3.1.  Set and save a borrowable content type.  (Currently the module supports only one).
3.2.  Set and save a cck nodereference field which links your borrowable item records to a 
      bibliographic record. 
3.3.  (Optionally, you may also set one or more Profile fields which correspond to user names.  
       This makes it a bit easier to use the autocomplete function to fill out usernames
       when checking out items.)


Authors
-------

A 5.x version of the module was built by Zachary Howarth-Schueler.
A 6.x port was created by Chris Ritzo at the Champaign-Urbana IMC.
The 6.x port was heavily modified again by Zachary Howarth-Schueler for the Youth Project library (youthproject.ns.ca)
A 7.x port is currently underway, again by Zachary Howarth-Schueler.

Ongoing maintenance is done by Zachary Howarth-Schueler.

