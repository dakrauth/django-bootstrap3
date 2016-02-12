=========================
Template tags and filters
=========================


.. note::

 For the following examples, it is understood that you have already loaded the ``bootstrap3``
 template tag library, placing the code below in the beginning that each template that ``bootstrap3``
 template tag library will be used. Read the :doc:`installation` and :doc:`quickstart` sections on how
 to accomplish this.

Common Keyword Arguments
------------------------

The following table lists the optional keyword arguments common to 
``bootstrap_form``, ``bootstrap_formset``, and ``bootstrap_field``.

==========================  ================  =======================================
Variable                    Default           Description
==========================  ================  =======================================
``layout``                  ``''``            
``form_group_class``        ``'form-group'``  
``field_class``             ``''``            
``label_class``             ``''``            
``show_help``               ``True``          
``show_label``              ``True``          
``exclude``                 ``''``            
``set_required``            ``True``          
``set_disabled``            ``False``         
``size``                    ``''``            Options: ``'sm'``, ``'small'``, 
                                              ``'md'``, ``'medium'``, ``'lg'``, 
                                              or ``'large'``.
``horizontal_label_class``  ``'col-md-3'``    
``horizontal_field_class``  ``'col-md-9'``    
==========================  ================  =======================================


bootstrap_form
~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_form


bootstrap_form_errors
~~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_form_errors


bootstrap_formset
~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_formset


bootstrap_formset_errors
~~~~~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_formset_errors


bootstrap_field
~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_field


bootstrap_label
~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_label


bootstrap_button
~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_button


bootstrap_icon
~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_icon


buttons
~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_buttons


bootstrap_messages
~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_messages


bootstrap_pagination
~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_pagination


bootstrap_jquery_url
~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_jquery_url


bootstrap_javascript_url
~~~~~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_javascript_url


bootstrap_css_url
~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_css_url


bootstrap_css
~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_css


bootstrap_javascript
~~~~~~~~~~~~~~~~~~~~

.. autofunction:: bootstrap3.templatetags.bootstrap3.bootstrap_javascript
