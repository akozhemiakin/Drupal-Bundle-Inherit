Description:
  Allow end users to inherit new node type from the existing one.

  There are two types of inheritance (two modes):
  Soft - Creates new content type and copy fields from existing type.
  Strict - Creates new content type, copy field from existing one and keep 
  those types synchronized:
  - When you add new field to the parent type, this field will be also attached 
    to the children types.
  - When you update field instance in the parent type, this instance also will 
    be updated in the children types.
  Also, using strict mode end user will not be able to directly edit or delete 
  fields instances inherited from parent type. All inherited fields will be 
  unlocked if the parent type will be removed.

Module project page:
  http://drupal.org/sandbox/lemark/1313824

Demo:
  http://demo.etreyd.com/

  User: demo
  Password: demo
  
To submit bug reports and feature suggestions, or to track changes:
  http://drupal.org/project/issues/1313824

-- MAINTAINERS --

lemark - http://drupal.org/user/317870