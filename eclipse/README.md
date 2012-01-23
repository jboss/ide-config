JBoss IDE Configuration Files For Eclipse
=========================================
The following instructions cover how to configure eclipse to use files and conventions to comply with JBoss coding standards.

(version 3.7 used)

Java Formatter
--------------
(Ctrl+Shift+F by default)
 
1. Download the jboss-java-formatter.xml file in this directory.
2. In Eclipse preferences go to Java -> Code Style -> Formatter
3. Click Import
4. Select the formatting file you downloaded in step (1)

Java Clean up
-------------
(not bound by default, use  of Ctrl+Shift+O recommended)
 
1. Download the jboss-java-cleanup.xml file in this directory.
2. In Eclipse preferences for to Java -> Code Style -> Clean-up
3. Click Import
4. Select the clean-up file you downloaded in step (1)
 
*Map the Clean-up Rules to Ctrl+Shift+O*

1. You may have to unbind Ctrl+Shift+O from "Organise imports" action first
2. In Eclipse preferences go to General -> Keys
3. Type "clean" into filter input ("type filter text")
4. Select Clean-up
5. Setup Binding: focus the input and type Ctrl+Shift+O as individual keys (or any other preferred shortcut)

Java Templates
--------------
Will create proper JBoss copyright headers for new Java class files.

1. Download the jboss-java-templates.xml file in this directory.
2. In Eclipse preferences for to Java -> Code Style -> Code Templates
3. Click Import
4. Select the clean-up file you downloaded in step (1)

JavaScript Formatter
--------------------
(Ctrl+Shift+F by default)
 
1. Download the jboss-js-formatter.xml file in this directory.
2. In Eclipse preferences go to JavaScript -> Code Style -> Formatter
3. Click Import
4. Select the formatting file you downloaded in step (1)

JavaScript Clean Up 
-------------------
(not bound by default, use  of Ctrl+Shift+O recommended - see above)
 
1. Download the jboss-js-cleanup.xml file in this directory.
2. In Eclipse preferences for to JavaScript -> Code Style -> Clean-up
3. Click Import
4. Select the clean-up file you downloaded in step (1)

JavaScript Templates
--------------------
Will create proper JBoss copyright headers for new JavaScript files.

1. Download the jboss-js-templates.xml file in this directory.
2. In Eclipse preferences for to JavaScript -> Code Style -> Code Templates
3. Click Import
4. Select the clean-up file you downloaded in step (1)

General Text Editor Formatting
------------------------------
1. In Eclipse Preferences go to General -> Editors -> Text Editors
2. Setup
 * Insert spaces for tabs: YES
 * Show print margin: YES
 * Print margin column: 128

XML formatting
--------------
1. In Eclipse Preferences go to XML -> XML Files -> Editor
2. Setup
 * Line width: 128
 * Split multiple attributes each on new line: NO
 * Align final bracked in multi-line element tags: NO
 * Preserve whitespace in tags with PCDATA content: NO
 * Clear all blank lines: NO
 * Format comments: NO
 * Insert whitespace before closing empty eng-tags: YES
 * Indent using spaces
 * Indentation size: 4

HTML formatting
---------------
1. In Eclipse Preferences go to -> Web -> HTML Files -> Editor
2. Setup
 * Line width: 128
 * Split multiple attributes each on new line: NO
 * Align final bracked in multi-line element tags: NO
 * Clear all blank lines: NO
 * Indent using spaces
 * Indentation size: 4
 * Tag names: Lowercase
 * Attribute names: Lowercase

CSS Formatting
--------------

1. In Eclipse Preferences go to Web -> CSS Files -> Editor
2. Setup
 * Line width: 128
 * Insert line break between properties: YES
 * Disable wrapping in style attribute of Html: YES
 * Indent using spaces
 * Indentation size: 4
 * Capitalization style: all Lowercase

CSS Templates
-------------
Will create proper JBoss copyright headers for new CSS files.

1. Download the jboss-css-templates.xml file in this directory.
2. In Eclipse preferences go to Web -> CSS Files -> Editor -> Templates
3. Click Import
4. Select the clean-up file you downloaded in step (1)



