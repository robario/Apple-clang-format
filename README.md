Apple-like Clang-format
=======================

Trying to make a .clang-format file as similar as you can get to Apples code style.


```yaml
---
Language:        Cpp
# BasedOnStyle:  LLVM
AccessModifierOffset: -2
ConstructorInitializerIndentWidth: 4
AlignEscapedNewlinesLeft: false
AlignTrailingComments: true
AllowAllParametersOfDeclarationOnNextLine: true
AllowShortIfStatementsOnASingleLine: false
AllowShortLoopsOnASingleLine: false
AllowShortFunctionsOnASingleLine: false
AlwaysBreakTemplateDeclarations: false
AlwaysBreakBeforeMultilineStrings: false
BreakBeforeBinaryOperators: false
BreakBeforeTernaryOperators: true
BreakConstructorInitializersBeforeComma: false
BinPackParameters: true
ColumnLimit:     140
ConstructorInitializerAllOnOneLineOrOnePerLine: false
DerivePointerBinding: false
ExperimentalAutoDetectBinPacking: false
IndentCaseLabels: false
MaxEmptyLinesToKeep: 1
NamespaceIndentation: None
ObjCSpaceAfterProperty: true
ObjCSpaceBeforeProtocolList: true
PenaltyBreakBeforeFirstCallParameter: 19
PenaltyBreakComment: 300
PenaltyBreakString: 1000
PenaltyBreakFirstLessLess: 120
PenaltyExcessCharacter: 1000000
PenaltyReturnTypeOnItsOwnLine: 60
PointerBindsToType: false
SpacesBeforeTrailingComments: 1
Cpp11BracedListStyle: true
Standard:        Cpp11
IndentWidth:     4
TabWidth:        8
UseTab:          Never
BreakBeforeBraces: Stroustrup
IndentFunctionDeclarationAfterType: true
SpacesInParentheses: false
SpacesInAngles:  false
SpaceInEmptyParentheses: false
SpacesInCStyleCastParentheses: false
SpacesInContainerLiterals: true
SpaceBeforeAssignmentOperators: true
ContinuationIndentWidth: 4
CommentPragmas:  '^ IWYU pragma:'
SpaceBeforeParens: ControlStatements
...


```