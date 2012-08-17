---
layout: scalastyle
title: "Scalastyle - Release notes"
---

Version 0.1.0
=============

The first release of Scalastyle.

The following checkers were added:

* ClassNamesChecker - Check that class names match a regular expression
* CovariantEqualsChecker - Check that classes and objects do not define equals without overriding equals(java.lang.Object).
* CyclomaticComplexityChecker - Checks that the cyclomatic complexity of a method does exceed a value
* EqualsHashCodeChecker - Check that if a class implements either equals or hashCode, it should implement the other
* FileLengthChecker - Check the number of lines in a file
* FileLineLengthChecker - Check the number of characters in a line
* FileTabChecker - Check that there are no tabs in a file
* HeaderMatchesChecker - Check the first lines of each file matches the text
* IfBraceChecker - Checks that if statement have braces
* IllegalImportsChecker - Check that a class does not import certain classes
* MagicNumberChecker - Checks for use of magic numbers
* MethodLengthChecker - Checks that methods do not exceed a maximum length
* MethodNamesChecker - Check that method names match a regular expression
* NewLineAtEofChecker - Checks that a file ends with a newline character
* NoCloneChecker - Check that classes and objects do not define the clone() method
* NoFinalizeChecker - Check that classes and objects do not define the finalize() method
* NoNewLineAtEofChecker - Checks that a file does not end with a newline character
* NoWhitespaceAfterLeftBracketChecker - No whitespace after left bracket '\['
* NoWhitespaceBeforeLeftBracketChecker - No whitespace before left bracket '\['
* NullChecker - Check that null is not used
* NumberOfMethodsInTypeChecker - Check that a class / trait / object does not have too many methods
* NumberOfTypesChecker - Checks that there are not too many types declared in a file
* ObjectNamesChecker - Check that object names match a regular expression
* PackageObjectNamesChecker - Check that package object names match a regular expression
* ParameterNumberChecker - Maximum number of parameters for a method
* PublicMethodsHaveTypeChecker - Check that a method has an explicit return type, it is not inferred
* RegexChecker - Checks that a regular expression cannot be matched, if found reports this
* ReturnChecker - Check that return is not used
* SimplifyBooleanExpressionChecker - Boolean expression can be simplified
* SpacesAfterPlusChecker - Check that the plus sign is followed by a space
* SpacesBeforePlusChecker - Check that the plus sign is preceded by a space
* StructuralTypeChecker - Check that structural types are not used.
* UppercaseLChecker - Checks that if a long literal is used, then an uppercase L is used
* VarFieldChecker - Checks that classes and objects do not define mutable fields
* VarLocalChecker - Checks that functions do not define mutable variables
* WhileChecker - Checks that while is not used
* WhitespaceEndOfLineChecker - Check that there is no trailing whitespace at the end of lines
