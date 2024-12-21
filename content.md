```
Tell us about your PDF experience.
```
## Feedback

**Was this page helpful?**

Provide product feedback

# AL Language reference overview

Article•11/25/

This section contains reference articles for AL for Business Central. You'll find the
documentation divided into groups; diagnostics, AVS diagnostics, data types and
methods, method attributes, properties, and triggers. Use **Filter by title** in the upper left
corner to search, if you already know the name of a method, trigger, or have a
diagnostics error number.

Get started with AL

## Related information

```
 Yes  No
```

# AL Compiler Diagnostics

Article•05/14/

```
Id Message Default
Severity
```
```
AL0100 Unterminated multiline comment. Error
AL0101 Constant value '{0}' is outside the range for a Decimal. Error
```
```
AL0102 Constant value '{0}' is outside the range for a BigInteger. Error
AL0103 Constant value '{0}' is outside the range for an Integer. Error
```
```
AL0104 Syntax error, '{0}' expected. Error
AL0105 Syntax error, identifier expected; '{1}' is a keyword. Error
```
```
AL0106 Syntax error, 'TO' or 'DOWNTO' expected. Error
AL0107 Syntax error, identifier expected. Error
```
```
AL0108 Indexers must have at least one value. Error
AL0109 Unexpected token. Error
```
```
AL0110 Orphaned ELSE statement. This is most likely because of an unnecessary
semicolon placed just before the ELSE keyword.
```
```
Error
```
```
AL0111 Semicolon expected. Error
```
```
AL0112 {0} is not a valid attribute. Error
AL0113 At least one dimension must be specified. Error
```
```
AL0114 Syntax error, integer literal expected. Error
AL0115 Object type expected. Error
```
```
AL0116 Invalid value for '{0}'. Allowed values are '{1}'. Error
AL0117 Illegal statement. Only assignment and method invocation can be used as a
statement.
```
```
Error
```
```
AL0118 The name '{0}' does not exist in the current context. Error
```
```
AL0119 The parameter name '{0}' is already defined. Error
```
```
ﾉ Expand table
```

**Id Message Default
Severity**

AL0120 A local or parameter named '{0}' cannot be declared in this scope because
that name is used in an enclosing local scope to define a local or parameter.

```
Error
```
AL0121 The variable name '{0}' is already defined. Error

AL0122 Cannot implicitly convert type '{0}' to '{1}'. Error

AL0123 The return value name '{0}' is already defined. Error

AL0124 The property '{0}' cannot be used in this context. Error

AL0125 Method name expected. Error

AL0126 No overload for method '{0}' takes {1} arguments. Candidates: {2}. Error

AL0127 Member '{0}' cannot be used like a method. Error

AL0128 Language identifier expected. Error

AL0129 The left-hand side of an assignment must be a variable or field. Error

AL0130 A 'var' argument must be an assignable variable. Error

AL0131 The property CharAllowed must be specified in pairs of characters. The first
character in the pair must be equal to or less than the second.

```
Error
```
AL0132 '{0}' does not contain a definition for '{1}'. Error

AL0133 Argument {0}: cannot convert from '{1}' to '{2}'. Error

AL0134 '{0}' is not recognized as a valid type. Error

AL0135 There is no argument given that corresponds to the required formal
parameter '{0}' of '{1}'.

```
Error
```
AL0136 The loop variable in a 'for' statement must be a numeric type. Error

AL0137 No enclosing loop out of which to break. Error

AL0138 The case expression cannot be an array. Error

AL0139 Since '{0}' doesn't have a return value, EXIT cannot be called with a value. Error

AL0140 The expression is not valid for the WITH statement. Error

AL0142 Only variables of type record can be marked as TEMPORARY. Error

AL0143 Cannot apply indexing with [] to an expression of type '{0}'. Error

AL0144 Wrong number of indices inside []; expected {0}. Error


**Id Message Default
Severity**

AL0145 Assignment is not valid for arrays. Error

AL0146 The maximum number of array elements is {0}. Actual number is {1}. Error

AL0147 An array dimension must be a positive number. Error

AL0148 The table filter is not valid. Error

AL0149 There is an 'ELSE' statement without an 'IF' in property {0}. Error

AL0150 Invalid CONST expression. A valid integer or an identifier is expected. Error

AL0151 Expression must be an Option. Error

AL0152 The value '{0}' is used more than once. Error

AL0153 The property '{0}' cannot be blank. Error

AL0154 The maximum length for a field of type '{0}' is {1}. Error

AL0155 A member of type {0} with name '{1}' is already defined in {2} '{3}' by the
extension '{4}'.

```
Error
```
AL0156 '{0}' is not a valid field type. Error

AL0157 '{0}' is not a valid variable type. Error

AL0158 '{0}' is not a valid parameter type. Error

AL0159 '{0}' is not a valid return type. Error

AL0160 '{0}' is not a valid language identifier. Error

AL0161 '{0}' is inaccessible due to its protection level. Error

AL0162 '{0}' is not a valid trigger. Error

AL0163 Wrong signature. Correct signature for '{0}' is '{1}'. Error

AL0164 The trigger '{0}' is already defined. Error

AL0165 Triggers cannot be called directly. Error

AL0166 Argument {0}: must be a member. Error

AL0167 The {0} '{1}' can only be used if the property '{2}' is set with any of the values
of: '{3}'.

```
Error
```
AL0168 The {0} '{1}' can only be used if the property '{2}' is set. Error


**Id Message Default
Severity**

AL0169 The option value '{0}' is not valid. Error

AL0170 An '=' is expected for property {0}. Error

AL0171 The property value '{0}' on property '{1}' is not valid. Error

AL0172 Operator '{0}' is ambiguous on an operand of type '{1}'. Error

AL0173 Operator '{0}' cannot be applied to an operand of type '{1}'. Error

AL0174 Operator '{0}' is ambiguous on operands of type '{1}' and '{2}'. Error

AL0175 Operator '{0}' cannot be applied to operands of type '{1}' and '{2}'. Error

AL0176 Expected one of the calculation formula methods
(Average,Count,Exist,Min,Max,Lookup,Sum).

```
Error
```
AL0177 Invalid application object identifier. A number or an application object name
is expected.

```
Error
```
AL0178 A 'FILTER' keyword or an identifier is expected. Error

AL0179 An identifier or a member access expression is expected. Error

AL0180 A 'FILTER' keyword is expected. Error

AL0181 Invalid filter expression. Error

AL0182 An identifier or a literal is expected as the value of a filter expression. Error

AL0183 Unexpected character '{0}'. Error

AL0184 The expression '{0}' is not valid. Error

AL0185 {0} '{1}' is missing. Error

AL0186 Reference '{0}' in application object '{1}' does not exist. Error

AL0187 Attribute '{0}' is valid only for {1}. Error

AL0189 Attribute '{0}' cannot be specified, because '{1}' is already specified. Error

AL0190 Constant value '{0}' is outside the range for a Time. Error

AL0191 Constant value '{0}' is outside the range for a Date. The syntax for defining
Date format is yyyymmddD, where D is a mandatory letter. For example,
20180325D, read as the 25th of March, 2018.

```
Error
```
AL0192 The return value must be used for the method '{0}'. Error


**Id Message Default
Severity**

AL0193 Argument {0}: cannot convert from '{1}' to the type of Argument 1 '{2}'. Error

AL0195 Invalid permission kind. Expected: '{0}'. Error

AL0196 The call is ambiguous between the method '{0}' defined in {1} '{2}' by the
extension '{3}' and the method '{4}' defined in {5} '{6}' by the extension '{7}'.

```
Error
```
AL0197 An application object of type '{0}' with name '{1}' is already declared by the
extension '{2}'.

```
Error
```
AL0198 Expected one of the application object keywords ({0}). Error

AL0199 The type of the sum index field '{0}' must be numeric (Decimal, BigInteger,
Integer, or Duration).

```
Error
```
AL0200 Property '{0}' is obsolete and will be removed in a future version. Warning

AL0201 The {0} FlowField is not a Boolean field. If a FlowField CalcFormula starts
with 'Exist', then the FlowField must be a Boolean type field.

```
Error
```
AL0202 The {0} FlowField is not an Integer field. If a FlowField CalcFormula starts
with 'Count', then the FlowField must be an Integer type field.

```
Error
```
AL0203 Cannot calculate Sum or Average for the field {0} because it is not a numeric
field (Decimal, BigInteger, Integer, or Duration data type).

```
Error
```
AL0204 Field type {0} is not convertible to field type {1}. Error

AL0206 A field with ID {0} is already defined in {1} '{2}' by the extension '{3}'. Error

AL0207 The expression must be of Text type. Error

AL0208 The expression must be of Boolean type. Error

AL0210 A control with ID = {0} is already defined. Error

AL0211 Unknown area type '{0}'. Error

AL0212 An area of type '{0}' is already defined. Error

AL0213 An area of type '{0}' is only valid on pages of type(s) '{1}'. Error

AL0214 An area of type 'FactBoxes' is not valid on Part type pages. Error

AL0215 A Part type page cannot contain other parts. Error

AL0216 Only parts are valid in an area of type 'FactBoxes'. Error

AL0217 Only parts and groups are valid in an area of type 'RoleCenter'. Error


**Id Message Default
Severity**

AL0218 An integer literal value is expected for property {0}. Error

AL0219 Syntax error, string literal expected. Error

AL0220 Syntax error, boolean literal expected. Error

AL0221 The value '{0}' is not valid. The valid range is {1}..{2}. Error

AL0222 The ID '{0}' is not valid. ID's must be greater than zero. Error

AL0223 The {0} '{1}' can only be used if the property '{2}' is set to '{3}'. Error

AL0224 Expression expected. Error

AL0227 A key with ID {0} is already defined. Error

AL0228 A field group with ID {0} is already defined. Error

AL0229 The data type on the {0} field is not valid because the ExtendedDatatype
property is set to Ratio. Valid data types are Integer, BigInteger and Decimal.

```
Error
```
AL0230 The data type on the {0} field is not valid because the ExtendedDatatype
property is set to PhoneNo, URL or Email. Valid data types are Code and
Text.

```
Error
```
AL0231 A member with ID '{0}' is already defined in {1} '{2}' by the extension '{3}'. Error

AL0232 The property value on field '{0}' must be positive or zero. Error

AL0234 An action with ID = {0} is already defined. Error

AL0235 The expression CONST() on the option value '{0}' is obsolete. Use CONST(" ")
to refer to the empty option value.

```
Warning
```
AL0236 An empty CONST() expression is not allowed on field '{0}' of type '{1}'. Error

AL0238 No overload for attribute '{0}' expects {1} arguments. Error

AL0239 Attribute {0} is specified multiple times. Error

AL0240 The signature of procedure '{0}' does not match the signature required by
attribute '{1}': parameter {2} is expected to be of type '{3}' but found type
'{4}'. The expected signature is: {5}.

```
Error
```
AL0241 The signature of procedure '{0}' does not match the signature required by
attribute '{1}'. The expected signature is: {2}.

```
Error
```
AL0242 Invalid attribute argument syntax: '{0}'. Error

AL0243 Attribute {0} can only be used within a codeunit of subtype {1}. Error


**Id Message Default
Severity**

AL0244 The signature of procedure '{0}' does not match the signature required by
attribute '{1}': return value is expected to be of type '{2}' but found type '{3}'.
The expected signature is: {4}.

```
Error
```
AL0245 The signature of procedure '{0}' does not match the signature required by
attribute '{1}': procedure cannot be local.

```
Error
```
AL0246 The property '{0}' cannot be customized. Error

AL0247 The target {0} '{1}' for the extension object is not found. Error

AL0250 The data type on the {0} field is not valid because the ExtendedDatatype
property is set to Person. Valid data types are Media and MediaSet.

```
Error
```
AL0251 Application object '{0}' is missing. Warning

AL0252 Expected 'Ascending' or 'Descending' value. Error

AL0254 Sorting field '{0}' should be part of the keys for table '{1}'. Warning

AL0255 Property '{0}' requires an application object reference for the 'RunObject'
property.

```
Error
```
AL0256 The flowfield '{0}' cannot be part of the keys for table '{1}'. Error

AL0257 Constant value '{0}' is outside the range for a DateTime data type, only 0 is
valid.

```
Error
```
AL0259 A SQLIndex defined for the primary key must contain the same fields as the
key for table '{0}'.

```
Error
```
AL0260 The key '{0}' on table '{1}' cannot start with the fields defined for the primary
key. The server will append these to any alternate key.

```
Error
```
AL0261 The identifier '{0}' can only be specified in the list once. Error

AL0262 The clustered key '{0}' has already been defined for table '{1}'. Error

AL0263 The primary key '{0}' on table '{1}' (the first one in the key list) must be
enabled.

```
Error
```
AL0264 An application object of type '{0}' with ID '{1}' is already declared by the
extension '{2}'.

```
Error
```
AL0267 Actions are not allowed on the control type. Error

AL0268 Grouping of actions is not allowed. Error

AL0269 The referenced page '{0}' should be a list part or a card part. Warning


**Id Message Default
Severity**
(Future Error)

AL0270 The control '{0}' is not found in the target '{1}'. Error

AL0271 The action '{0}' is not found in the target '{1}'. Error

AL0272 The anchoring symbol '{0}' must be a grouping symbol. Error

AL0273 The name '{0}' is an Area type. Using an Area type name will limit
extensibility as dependent extension won't be able to reference it.

```
Warning
(Future Error)
```
AL0274 The anchoring symbol '{0}' cannot be an area. Error

AL0275 '{0}' is an ambiguous reference between '{1}' defined by the extension '{2}'
and '{3}' defined by the extension '{4}'.

```
Error
```
AL0276 A Time literal value is expected for property {0}. Error

AL0277 A Date literal value is expected for property {0}. Error

AL0278 A DateTime literal value is expected for property {0}. Error

AL0279 The key '{0}' on table '{1}' contains too many fields. Error

AL0280 The event '{0}' is not found in the target. Error

AL0281 Object member '{0}' is not an event. Error

AL0282 The member referenced by event subscriber '{0}' parameter '{1}' is not
found.

```
Error
```
AL0283 The event '{0}' must not have a return value. Error

AL0284 The type of the parameter '{1}' on the event subscriber '{0}' does not match
the expected type '{2}'.

```
Error
```
AL0285 The event '{0}' must not have a parameter name 'sender' when it specifies to
include sender.

```
Error
```
AL0286 The event '{0}' can't contain code. Error

AL0287 The event '{0}' can't contain local variables. Error

AL0288 Parameter '{0}' is only allowed to be 'var' if the publisher parameter is 'var'. Error

AL0290 Element name is not allowed for the event '{0}' and must be empty. Error

AL0291 Event trigger '{0}' can only be used if the page specifies the 'SourceTable'
property.

```
Error
```

**Id Message Default
Severity**

AL0292 'FIELD', 'CONST' or 'FILTER' keyword is expected. Error

AL0293 Property value {0} is not in the field's OptionMembers. Error

AL0294 The type of property value {0} does not match the field’s type. Error

AL0295 The field '{0}' is not found in the target '{1}'. Error

AL0296 The application object or method '{0}' has scope '{1}' and cannot be used for
'{2}' development.

```
Error
```
AL0297 The application object identifier '{0}' is not valid. It must be within the
allowed ranges '{1}'.

```
Error
```
AL0298 The data type of the expression assigned to the 'StyleExpr' property is not
valid. Valid data types are Boolean, Text, or Code.

```
Error
```
AL0299 Member name '{0}' is only allowed on triggers. Warning
(Future Error)

AL0300 The property '{0}' is used as a method. Error

AL0301 A list must end with a member; not a separator {0}. Error

AL0302 Cannot use '{0}' in {1} '{2}' before it is declared. Error

AL0303 Attributes can only be defined on variables and methods. Error

AL0304 Length of the identifier '{0}' cannot exceed {1} characters. Error

AL0305 The length of the application object identifier '{0}' cannot exceed {1}
characters.

```
Error
```
AL0306 A field list has to contain at least one field. Error

AL0307 Property value cannot be validated because the source table is unreachable. Error

AL0308 The primary key '{0}' on table '{1}' (the first one in the key list) must have the
MaintainSqlIndex property set to true.

```
Error
```
AL0309 Table '{0}' contains too many keys. Error

AL0310 An instance is required for the non-static member '{0}'. Error

AL0311 Member '{0}' cannot be accessed with an instance reference; qualify it with
'{1}' instead.

```
Error
```
AL0313 Attribute {0} can only be used within {1}. Error

AL0314 The property '{0}' is only valid in controls of type '{1}'. Error


**Id Message Default
Severity**

AL0315 Control '{0}' does not exist in group '{1}'. Error

AL0316 The expression must be of Integer type. Error

AL0317 A property with the same name has already been declared. Error

AL0318 The value assigned to the 'RunObject' property is not valid. Valid object
types are codeunit, page, xmlport, report, and query.

```
Error
```
AL0319 At least one target has to be specified for the move. Error

AL0320 The referenced page '{0}' must specify a 'SourceTable'. Error

AL0321 Variable {0} cannot be included in the data set. Error

AL0322 {0} is not valid for client expressions. Error

AL0323 The value assigned to the SystemPart type is not valid. Valid values are {0}. Error

AL0324 The language {0} must only be specified one time. Error

AL0325 The field '{0}' in the table '{1}' cannot be included in a key because its type is
'{2}'.

```
Error
```
AL0326 '{0}' is not a valid column type. Error

AL0327 Missing file '{0}'. Error

AL0329 The {0} property must reference a top-level DataItem. Error

AL0331 The property 'DataItemLink' cannot be set on a top-level DataItem. Error

AL0332 The control {0} must be of type {1}. Error

AL0333 The syntax for accessing fields is not valid. Specify target field with
'tableName.fieldName' syntax.

```
Error
```
AL0334 The extension object '{0}' cannot be declared. Another extension for target
'{1}' or the target itself is already declared in this module.

```
Error
```
AL0335 Attributes must be specified before elements inside of an element. Error

AL0336 There must be exactly one root node and it has to be an element. Error

AL0337 None of the specified parent table elements has the name {0}. Error

AL0338 Event trigger '{0}' can only be used if the page specifies 'SourceTable'. Table
'{1}' is missing.

```
Error
```
AL0340 Page '{0}' should be of type 'RoleCenter'. Error


**Id Message Default
Severity**

AL0341 '{0}' property is missing. Error

AL0342 You cannot combine two DataItems at the same level because unions are
not supported.

```
Error
```
AL0343 Queries must define a top-level DataItem. Error

AL0344 The property 'DataItemLink' must be set. Error

AL0345 The source of a Column or Filter must be a field defined on the table
referenced by its parent DataItem.

```
Error
```
AL0346 The methods '{0}' can only be used on Columns that have a Date or
DateTime type.

```
Error
```
AL0347 The methods '{0}' can only be used on Columns that have a Decimal,
BigInteger, Integer, or Duration type.

```
Error
```
AL0349 Column '{0}' does not exist in application object '{1}'. Error

AL0350 The column '{0}' cannot be used multiple times when defining the order of
the resulting dataset.

```
Error
```
AL0351 The property 'DataItemLink' can only reference fields on ancestor data
items.

```
Error
```
AL0352 Queries must define at least one Column. Error

AL0353 A Column must have a valid data source or have the 'Method' property set
to 'Count'.

```
Error
```
AL0354 Cannot move element '{0}' relative to itself in page '{1}'. Error

AL0355 Cannot move the {0} '{1}' multiple times inside of a single move operation. Error

AL0356 Cannot modify the {0} '{1}' multiple times. Error

AL0357 Cannot add {0} '{1}' with the same name multiple times. Error

AL0358 Cannot move or modify the {0} '{1}' in the same '{2}' that you added. Error

AL0359 The XML node name is not valid. {0}. Error

AL0360 Text literal was not properly terminated. Use the character ' to terminate the
literal.

```
Error
```
AL0361 Identifier was not properly terminated. Use the character " to terminate the
identifier.

```
Error
```
AL0362 The path must be relative to the project root. Error


**Id Message Default
Severity**

AL0363 The directory separator used in this property value is not compatible with
the current operating system.

```
Error
```
AL0364 Option members must be accessed with ::. Error

AL0365 The property '{0}' cannot be set if the property '{1}' is set to '{2}'. Error

AL0366 A table has to have at least one Normal field. Error

AL0367 An array must have at least one dimension. Error

AL0368 The maximum number of array dimensions is {0}. Error

AL0369 Constant value '{0}' cannot be converted to a '{1}'. Error

AL0370 Division by constant zero. Error

AL0371 The operation overflows at compile time. Error

AL0372 The length of the String constant exceeds the current memory limit. Error

AL0373 The XML name cannot be empty. Error

AL0374 The use of a unique ID has been deprecated and the ID can be removed. Warning

AL0375 Option members cannot contain comma. Error

AL0376 A control of type '{0}' is not allowed in a parent control of type '{1}'. Error

AL0377 '{0}' is not a valid value for the '{1}' attribute on variables of type '{2}'. Error

AL0378 A page of type Role Center cannot have triggers. Error

AL0379 The name '{0}' cannot be used as an identifier because it does not comply
with the Common Language Specification.

```
Error
```
AL0380 Cannot move symbol '{0}' from '{1}' area to '{2}' area. Error

AL0381 The keys '{0}' and '{1}' have an identical list of fields. Error

AL0382 The option value '{0}' is defined more than once on field '{1}'. Error

AL0383 The option value '{0}' is not defined on field '{1}'. Error

AL0384 The name of all the columns and all the labels defined in a report must be
unique.

```
Error
```
AL0385 IncludeCaption can be set to true only if the source of the column is a
named field.

```
Error
```

**Id Message Default
Severity**

AL0386 A required package dependency could not be found. Make sure that you
have downloaded all the referenced packages and their dependencies.

```
Error
```
AL0387 Namespace '{0}' is already specified. Error

AL0388 The date formula '{0}' must include plus (+) or minus (-). Error

AL0389 The date formula '{0}' contains a number that is too large. The number must
be in the range {1} - {2}.

```
Error
```
AL0390 The date formula '{0}' must include a time unit. Time units can be:
D,WD,W,M,Q, or Y. C specifies the current time unit based on date and can
be used as a prefix to any of the time units.

```
Error
```
AL0391 The date formula '{0}' must include a number. Error

AL0392 The input cannot be longer than {0}. Error

AL0393 Application object {0} is already referenced. Error

AL0395 You can only specify Move and Modify actions in the layout section of a
page customization.

```
Error
```
AL0396 Procedures and triggers are not allowed on page customizations. Error

AL0397 The name '{0}' clashes with '{1}' column's format column name. Error

AL0398 Constant value '{0}' is outside of the valid ordinal range for this {1} type. Error

AL0399 Global variables are not allowed on page customizations. Error

AL0401 Multiple page customizations have been specified for the same page {0}
within the same profile.

```
Error
```
AL0402 Expression {0} cannot be specified more than once in a 'case' statement. Error

AL0403 To modify '{0}' you must add at least one property or trigger. Error

AL0404 Property '{0}' is not allowed on a table extension. Error

AL0405 An option value is expected. Error

AL0406 The type for {0} is not valid. Expected {1}, but found {2}. Error

AL0407 The generic '{0}' type expects {1} type arguments. Error

AL0408 The type '{0}' cannot be used as a type argument in this context. Error

AL0409 The '{0}' type is not a generic type. Error


**Id Message Default
Severity**

AL0410 The report '{0}' doesn't contain a Request Page. Error

AL0411 {0} can be specified only once. Error

AL0412 Member '{0}' could not be declared in an object of type '{1}'. Error

AL0413 Procedure '{0}' cannot have a body. Error

AL0414 Procedure '{0}' must declare a body. Error

AL0415 Keyword 'local' cannot be specified for procedure '{0}'. Error

AL0416 Method '{0}' cannot have a return value. Error

AL0417 Control add-in '{0}' not found. Error

AL0418 The format of resource '{0}' is not valid. Resources in the control add-in
should either be relative to the project root, or reference external files using
the HTTP or HTTPS protocol.

```
Error
```
AL0419 The event subscriber '{0}' is missing a parameter of type '{1}'. Error

AL0420 Parameter '{0}' cannot be 'var'. Error

AL0421 A ‘foreach’ statement can only be used with an expression of an enumerable
type.

```
Error
```
AL0422 Constant value {0} is not a valid value for APIVersion. Valid values are 'beta'
or of type 'vX.Y' where X and Y represent positive integers.

```
Error
```
AL0423 The property '{0}' can only be set if the specified fields are from the same
table.

```
Error
```
AL0424 The multilanguage syntax should not be used because the app uses
translation files (the "features" property of the app.json includes
"TranslationFile"). Update the translation files and use the label syntax
instead.

```
Warning
```
AL0425 The '{0}' trigger can only be used on codeunits that have the Subtype
property set to '{1}'.

```
Error
```
AL0426 The APIVersion {0} is specified multiple times. Error

AL0427 Field {0} cannot be converted to type {1}. Error

AL0428 Cannot specify {0} and {1} property at the same time. Use only the {1}
property.

```
Error
```
AL0429 A repeater control can only be added to pages that have a source table. Error


**Id Message Default
Severity**

AL0430 The parameter '{0}' has a type which is not serializable and therefore cannot
be used in the given context.

```
Error
```
AL0432 {0} '{1}' is marked for removal. {2}. Warning

AL0433 {0} '{1}' is removed. {2}. Error

AL0434 Syntax error, numeric literal expected. Error

AL0435 Syntax error, literal expected. Error

AL0436 The value of the property '{0}' cannot be empty. Error

AL0437 The value of the '{0}' property cannot include empty members. Error

AL0438 The type of value {0} does not match the field’s type. Error

AL0439 The label's property is not valid. Possible properties are: {0}. Error

AL0440 The {0} '{1}' already defines a method called '{2}' with the same parameter
types in '{3}'.

```
Error
```
AL0441 Parameter {0} is only available when the page specifies a 'SourceTable'. Error

AL0442 Parameter {0} is only available when the page specifies a 'SourceTable'. Table
'{1}' is missing.

```
Error
```
AL0443 The system object provided is not one of the valid system objects. Error

AL0444 Malformed {0} report layout at location '{1}'. The issue is: '{2}'. Error

AL0445 The file '{0}' is opened in another application. Close the application to be
able to compile.

```
Error
```
AL0447 The value '{0}' for the property '{1}' cannot be used for '{2}' development. Error

AL0448 Member is not allowed in this context. Error

AL0449 The alias '{0}' is already declared. Error

AL0450 Field '{0}' is removed and cannot be used in an active key. Error

AL0451 An assembly named '{0}' could not be found in the assembly probing paths
'{1}'.

```
Error
```
AL0452 The type '{0}' could not be found in assembly '{1}'. Error

AL0453 This feature is under development. It can be enabled by using the '{0}'
feature flag.

```
Error
```

**Id Message Default
Severity**

AL0454 The {0} {1} of type {2} cannot be extended. Error

AL0455 Option ordinal value '{0}' is not valid. Valid values are -1 and positive
integers.

```
Error
```
AL0456 The number of option ordinal values is not valid. There must be as many
option ordinal values as there are option members.

```
Error
```
AL0457 The label syntax is not correct. Please move the '{0}' to its designated
attribute.

```
Warning
```
AL0458 '{0}' is not a valid attribute on variables of type '{1}'. Error

AL0459 The attribute '{0}' is only allowed on global variables. Error

AL0460 Client-side events are supported only on pages and page extensions. Error

AL0461 '{0}' is not a valid event publisher. Error

AL0462 The publisher '{0}' does not have any public events named '{1}'. Error

AL0463 Parameter '{0}' must be 'var' if and only if the publisher parameter is 'var'. Error

AL0464 Could not determine a suitable default primary key for table '{0}'. Please
specify a primary key for the table.

```
Error
```
AL0465 The property '{0}' does not accept references to external files. Error

AL0466 Cannot access file '{0}'. The file is most likely read-only. Error

AL0467 Cannot access file '{0}'. The file is most likely read-only. Warning

AL0468 Length of the table field name '{0}' must not exceed {1} characters. Longer
field names are prone to cause SQL errors.

```
Warning
(Future Error)
```
AL0470 The referenced page '{0}' of PageType 'HeadlinePart' is only allowed inside
pages of PageType 'RoleCenter'.

```
Error
```
AL0471 The format of link '{0}' is not valid. It should be using the HTTP or HTTPS
protocol.

```
Error
```
AL0472 The source of the translation item does not match the label value. Ignoring
the translation item.

```
Warning
```
AL0473 The translated string of the translation item is too long. Trimming the
translated string.

```
Warning
```
AL0474 The attribute '{0}' is only allowed on local variables. Error

AL0475 The attribute '{0}' cannot be used on variables of array type. Error


**Id Message Default
Severity**

AL0476 The trigger '{0}' can only be used if the property '{1}' of '{2}' is set. Error

AL0477 The trigger '{0}' can only be used if the property '{1}' of '{2}' is set to '{3}'. Error

AL0478 The trigger '{0}' can only be used if the property '{1}' of '{2}' is set with any of
the values of :'{3}'.

```
Error
```
AL0479 There must be only one translation item for each ID. Warning

AL0480 Attributes cannot have nested elements. Error

AL0481 The property Image can only be used on fields that are contained in a
CueGroup control.

```
Warning
(Future Error)
```
AL0482 The image {0} is not valid in this context. Warning

AL0483 The property Image cannot be used on nested Action Groups inside the
'Sections' area.

```
Warning
```
AL0484 The property '{0}' must be alphanumeric. Error

AL0485 The property '{0}' is mandatory for objects of type API. Error

AL0486 A member of type {0} with name '{1}' is already defined in {2} '{3}' by the
extension '{4}'.

```
Warning
(Future Error)
```
AL0487 The field '{0}' is not of field class 'Normal' and thus cannot be part of the {1}
list.

```
Error
```
AL0488 ControlAddIn name must not contain characters {0}. Error

AL0489 The property expression is not valid. A CONST or FILTER expression is
expected.

```
Error
```
AL0490 The property expression is not valid. A CONST, FIELD, or FILTER expression is
expected.

```
Error
```
AL0491 The property expression is not valid. One of the following expressions is
expected :
CONST,FIELD,FILTER,FIELD(FILTER(Identifier)),FIELD(UPPERLIMIT(Identifier)),or
FIELD(UPPERLIMIT(FILTER(Identifier))).

```
Error
```
AL0492 The RunObject property value of actions defined in the '{0}' area must only
reference pages of type 'List'.

```
Error
```
AL0493 The RunObject property value of actions defined in the '{0}' area must only
reference pages of type 'List'.

```
Warning
(Future Error)
```
AL0494 The action area '{0}' can only directly contain groups. Error


**Id Message Default
Severity**

AL0495 A member with ID '{0}' is already defined. Change the member name to
generate a new ID.

```
Error
```
AL0496 Attributes cannot be defined in this context. Error

AL0498 The attribute '{0}' can only be used on procedures that have the attribute
'{1}'.

```
Error
```
AL0499 The handler function {0} was not found. Make sure the procedure is defined
and has a handler attribute.

```
Error
```
AL0500 The HandlerFunctions attribute only accepts a string representing a comma
separated list of procedure names without spaces.

```
Error
```
AL0501 Eventsubscribers in test codeunits must use manual binding. Set the
property EventSubscriberInstance to Manual.

```
Error
```
AL0502 The LinkTable property must reference a table element node of the current
XMLPort.

```
Error
```
AL0503 Reference '{0}' in application object '{1}' is ambiguous. Error

AL0504 The enum '{0}' is not extensible. Error

AL0505 Pages of type API must have the 'DelayedInsert' property set to true. From
runtime 7.2, 'DelayedInsert' can be set to false if the 'Editable' property or
the 'InsertAllowed' property is set to false.

```
Error
```
AL0509 Constant value '{0}' is outside of the valid ordinal range for this option type. Warning

AL0510 The .NET type '{0}' is not a valid control add-in. Error

AL0511 The property 'IsControlAddIn' must be set on the .NET type '{0}' if the type
represents a .NET control add-in.

```
Error
```
AL0512 The manifest should define the 'supportedLocales' manifest property in
order to use a placeholder in the '{0}' property.

```
Error
```
AL0513 The FieldGroup '{0}' is not found in the target '{1}'. Error

AL0514 The symbol file is not valid. An enum with ID '{0}' is already defined with a
different name in module '{1}'.

```
Error
```
AL0515 The symbol file is not valid. An enum with name '{0}' is already defined with
a different ID in module '{1}'.

```
Error
```
AL0516 The symbol file is not valid. An enum with ID '{0}' and name '{1}' is already
defined in module '{2}', but with different values (OptionString).

```
Error
```

**Id Message Default
Severity**

AL0517 The link '{0}' specified in the HelpLink property must either contain one
placeholder with value 0 for the user locale, or no placeholders.

```
Error
```
AL0518 A method with name '{0}' possessing one Handler attribute is already
defined in this test codeunit.

```
Error
```
AL0519 '{0}' is not valid value in this context. Error

AL0520 {0} '{1}' is removed. {2}. Warning

AL0521 The primary key '{0}' on table '{1}' (the first one in the key list) must not have
the Unique property set.

```
Error
```
AL0522 Property value {0} is not in the values for enum '{1}'. Error

AL0523 The {0} '{1}' already defines a method called '{2}' with the same parameter
types in '{3}'.

```
Warning
(Future Error)
```
AL0524 The base type already defines a method called '{0}' with the same parameter
types.

```
Warning
(Future Error)
```
AL0525 The system or virtual table '{0}' cannot be extended. Error

AL0526 The referenced page '{0}' of type 'API' is only allowed inside pages of
PageType 'API'.

```
Error
```
AL0527 The SQL timestamp field '{0}' cannot be part of the keys for table '{1}'. Error

AL0528 The name of field controls in pages of the type API must be alphanumeric. Error

AL0529 The name of columns in queries of the type API must be alphanumeric. Error

AL0530 The maximum length for the type '{0}' is {1}. Error

AL0531 The page '{1}' of type 'API' and its subpage '{2}' of type 'API' in the control
'{0}' of type 'Part' must have the same value of property '{3}'.

```
Error
```
AL0532 The page '{1}' of type 'API' and its control '{0}' of type 'Part' must have the
same value of property '{2}'.

```
Error
```
AL0533 The view '{0}' is not found in the target '{1}'. Error

AL0534 Length of the table key name '{0}' must not exceed {1} characters. Longer
key names are prone to cause SQL errors.

```
Warning
(Future Error)
```
AL0535 The referenced page '{0}' must be a List part, a Card part, or an API page. Error

AL0536 Adding new controls in a view is not allowed. Error

AL0537 Declaring views is only supported on pages of type {0}. Error


**Id Message Default
Severity**

AL0538 Views only support setting one sorting direction on table fields. Error

AL0539 The field '{0}' cannot be used multiple times when defining the order of the
page view.

```
Error
```
AL0540 The view name '{0}' is not valid. Error

AL0541 The use of the variable '{0}' in the property value of '{1}' in view '{2}' is not
allowed.

```
Error
```
AL0542 The property {0} cannot be used on page '{1}' because this page does not
have a source table.

```
Error
```
AL0543 The manifest property 'contextSensitiveHelpUrl' must be set in order to use
the property 'ContextSensitiveHelpPage'.

```
Error
```
AL0544 The property 'ContextSensitiveHelpPage' cannot contain a placeholder. Error

AL0545 An area of type '{0}' is not valid on pages of type '{1}'. Warning
(Future Error)

AL0546 The control '{0}' cannot be modified in a view context because views only
support modifying controls defined in the Content area.

```
Error
```
AL0547 The event '{0}' should not expose global variables. Warning
(Future Error)

AL0548 Cannot move symbol '{0}' from '{1}' area to '{2}' area. Warning
(Future Error)

AL0549 Procedures and triggers are not allowed on page views. Error

AL0550 Groups defined in the action area '{0}' should only contain actions. Warning
(Future Error)

AL0551 The action area '{0}' can only contain actions. Warning
(Future Error)

AL0552 The action area '{0}' can only directly contain groups. Warning
(Future Error)

AL0553 You cannot add actions of type '{0}' in the action area '{1}' from a page
customization. You can only add actions of type '{2}'.

```
Error
```
AL0554 You can only specify Move and Modify actions in the actions section of a
page customization.

```
Error
```
AL0555 The RunObject property value of actions defined in the '{0}' area must only
reference objects of type {1}.

```
Error
```

**Id Message Default
Severity**

AL0556 The RunObject property value of actions defined in the '{0}' area must only
reference objects of type {1}.

```
Warning
(Future Error)
```
AL0557 The name of the codeunit local variable '{0}' is identical to a field in table
'{1}' and will shadow that table field.

```
Warning
```
AL0558 The name of the codeunit global variable '{0}' is identical to a field in table
'{1}'.

```
Warning
```
AL0559 A Part type page cannot contain other parts. Warning
(Future Error)

AL0560 Only parts and groups are valid in an area of type 'RoleCenter'. Warning
(Future Error)

AL0561 Only parts are valid in an area of type 'FactBoxes'. Warning
(Future Error)

AL0562 The value assigned to the SystemPart type is not valid. Valid values are {0}. Warning
(Future Error)

AL0563 A control of type '{0}' is not allowed in a parent control of type '{1}'. Warning
(Future Error)

AL0564 The object {0} '{1}' is not extensible. Error

AL0565 Fast publishing requires a built application file to be present. The '{0}'
application file contains a manifest which is not valid. Please rebuild the
application file before continuing with fast publishing.

```
Error
```
AL0566 The field '{0}' is using an Id {1} that is reserved for system fields. Error

AL0567 The field '{0}' is using the same name as a system-provided field and will
shadow that field.

```
Warning
```
AL0568 Groups defined in the action area '{0}' should only contain actions or
groups.

```
Warning
(Future Error)
```
AL0569 A page of type Role Center cannot have procedures. Warning
(Future Error)

AL0570 The symbol '{0}' results in the same translation ID as one or more other
symbols. Rename symbol to resolve the problem.

```
Error
```
AL0571 The property 'Description' should only be used for internal comments. Use
the property 'Caption' or 'CaptionML' in order to specify the profile caption
displayed to end users.

```
Warning
(Future Error)
```

**Id Message Default
Severity**

AL0572 I/O operations on the file or folder '{0}' resulted in an exception with the
Windows 32 error code '{1}'.

```
Error
```
AL0573 {0} is not valid for client expressions. Warning
(Future Error)

AL0574 This feature is under development and cannot be used in an extension. Error

AL0575 You cannot reference the {0} '{1}' because it is defined in the page
customization '{2}'.

```
Error
```
AL0576 The profile name '{0}' is not valid because it contains leading or trailing
spaces.

```
Error
```
AL0577 The view '{0}' cannot define layout changes because its property '{1}' is not
set to false.

```
Error
```
AL0578 The value for the property '{0}' is not valid because its length exceeds {1}
characters ({2} characters).

```
Error
```
AL0579 The value for the property '{0}' for the language code '{1}' is not valid
because its length exceeds {2} characters ({3} characters).

```
Error
```
AL0580 The field '{0}' is used by the system and cannot be specified as a table key. Error

AL0581 The length for the type '{0}' must be positive. Error

AL0582 '{0}' does not implement the interface member '{1}'. Error

AL0584 An interface member cannot have any variables. Error

AL0585 An interface cannot have any variables. Error

AL0586 The identifier contains characters that are not valid: {0}. Warning
(Future Error)

AL0587 '{0}' is already listed in the interface list. Error

AL0588 The type of parameter '{1}' on event subscriber '{0}' is of type 'Option', but
the expected type is '{2}'. Please update the subscriber type to match the
publisher.

```
Warning
```
AL0589 The name '{0}' is used across multiple columns and data items. This will
prevent extensibility of this column or data item.

```
Warning
(Future Error)
```
AL0590 The property {0} is only supported on {1}. Warning
(Future Error)

AL0591 The property {0} is only supported on {1}. Error


**Id Message Default
Severity**

AL0592 Compatibility: {0}. Warning

AL0593 The type of the parameter '{0}' on the event subscriber '{1}' has a smaller
capacity than the parameter type '{2}' on the publisher.

```
Warning
(Future Error)
```
AL0594 An error occurred during XML serialization of metadata for symbol: '{0}'.
Error: {1}.

```
Error
```
AL0595 '{0}' does not implement {1}. Error

AL0596 Value '{0}' does not implement interface '{1}' and there is no default
implementation for the mentioned interface.

```
Error
```
AL0598 Cannot move or modify the {0} '{1}' in the same '{2}' that you added. Warning
(Future Error)

AL0599 A control add-in with the same internal name '{0}' is already defined. Error

AL0600 The property '{0}' can only be set on elements of type Option. Warning
(Future Error)

AL0601 {0} '{1}' is removed. {2}. Warning
(Future Error)

AL0602 '{0}' is inaccessible due to its protection level. Warning
(Future Error)

AL0603 An implicit conversion is being performed from a value of type '{0}' to a
value of type '{1}'. This conversion can lead to unexpected runtime issues.

```
Warning
```
AL0604 Use of implicit 'with' will be removed in the future. Qualify with '{0}'. Warning
(Future Error)

AL0605 Use of implicit 'with' will be removed in the future. Qualify with '{0}'. Hidden

AL0606 The 'with' statement is deprecated and will be removed for cloud
development in a future release.

```
Warning
(Future Error)
```
AL0607 The 'with' statement is deprecated and will be removed for cloud
development in a future release.

```
Hidden
```
AL0608 The OrderBy property must specify at least one field on which to sort the
data.

```
Warning
(Future Error)
```
AL0609 Adding actions to CueGroups is not supported. Warning

AL0610 Moving actions in CueGroups is not supported. Warning

AL0611 Modifying actions in CueGroups is not supported. Warning


**Id Message Default
Severity**

AL0612 An interface member must be a 'procedure'. Error

AL0613 Wrong signature. Correct signature for '{0}' is '{1}'. Warning
(Future Error)

AL0614 The value '{0}' is not allowed for property '{1}'. Warning
(Future Error)

AL0615 Field '{0}' is not specified as a source expression on page '{1}'. All fields
specified in ODataKeyFields must be used as the source expression in a
page control.

```
Warning
(Future Error)
```
AL0616 Defining the contract '{0}' on interface '{1}' is not allowed because it is
matching a built-in procedure for codeunits.

```
Error
```
AL0617 Event trigger 'OnBeforeActionEvent' cannot be used because the action '{0}'
specifies the 'RunObject' property.

```
Warning
(Future Error)
```
AL0619 The attribute '{0}' on procedure '{1}' is not allowed. Add attribute
'ServiceEnabled' to the procedure or move it into an application object of
type API.

```
Error
```
AL0620 Preprocessor directives must appear as the first non-whitespace character
on a line.

```
Error
```
AL0621 Preprocessor directive expected. Error

AL0622 #endregion directive expected. Error

AL0623 #endif directive expected. Error

AL0624 Unexpected preprocessor directive. Error

AL0625 Cannot define/undefine preprocessor symbols after first token in file. Error

AL0626 Expected identifier or numeric literal. Warning

AL0627 Expected 'disable' or 'restore' keyword. Warning

AL0628 Unrecognized #pragma directive. Warning

AL0629 Preprocessor expression is not valid. Error

AL0630 Unrecognized escape sequence. Error

AL0631 Single-line comment or end-of-line expected. Error

AL0632 Closing parenthesis ')' expected. Error

AL0633 Expected 'disable', 'enable' or 'restore' keyword. Warning


**Id Message Default
Severity**

AL0634 Single-line comment or end-of-line expected. Warning

AL0635 A method with 'OnPrem' scope cannot be used as event subscriber. It will
fail at runtime when the publisher has 'Cloud' scope.

```
Warning
(Future Error)
```
AL0636 The data type on the field '{0}' is not valid because the ExtendedDatatype
property is set to RichText. Valid data types are Text, BigText and Blob.

```
Error
```
AL0637 The property 'NavigationPageId' must be defined on a page of pagetype
'API'.

```
Error
```
AL0638 'Variant' is not a valid column type for column '{0}' in report '{1}'. Error

AL0639 'Variant' is not a valid column type for column '{0}' in report '{1}'. Warning
(Future Error)

AL0640 XML comment has badly formed XML -- '{0}'. Warning

AL0641 Parameter '{0}' has no matching param tag in the XML comment for '{1}'
(but other parameters do).

```
Warning
```
AL0642 Missing XML comment for publicly visible type or member '{0}'. Warning

AL0643 XML comment is not placed on a valid language element. Warning

AL0644 XML comment has a param tag for '{0}', but there is no parameter by that
name.

```
Warning
```
AL0645 XML comment on '{1}' has a paramref tag for '{0}', but there is no parameter
by that name.

```
Warning
```
AL0646 XML comment has a duplicate param tag for '{0}'. Warning

AL0647 {0}. See also error AL{1}. Warning

AL0648 End-of-file found, '*/' expected. Error

AL0649 Comma is not supported in enum value names or in captions. Enum Value =
'{0}', Property = '{1}'.

```
Warning
(Future Error)
```
AL0650 The text with a length of {0} is longer than the MaxLength of {1} which
means that the text will be trimmed.

```
Warning
(Future Error)
```
AL0651 '{0}' cannot be contained since it causes a circular reference. Error

AL0652 The permission set '{0}' cannot contain itself. Error

AL0653 Ids are not supported as object reference. Error


**Id Message Default
Severity**

AL0654 The property value contains an unexpected file extension: {0}. The expected
extensions are {1}.

```
Error
```
AL0655 The property DataItemLinkReference can only refer to an ancestor DataItem. Warning
(Future Error)

AL0656 The {0} '{1}' cannot be used as an anchor because it is already defined in the
same '{2}'.

```
Error
```
AL0657 The property {0} is mandatory for ListParts and PageParts. Error

AL0658 Member name '{0}' is only allowed on triggers. Error

AL0659 The length of the enum identifier '{0}' should not exceed {1} characters as it
may result in runtime issues in cases where there are other enums with the
same first {1} characters.

```
Warning
```
AL0660 The property '{0}' cannot be customized. Warning
(Future Error)

AL0665 '{0}' is not a valid return type in runtime version '{1}'. The supported runtime
versions are: {2}.

```
Error
```
AL0666 '{0}' is not available in runtime version '{1}'. The supported runtime versions
are: {2}.

```
Error
```
AL0667 '{0}' is being deprecated in the versions: {1} {2}. Warning
(Future Error)

AL0668 This feature is not available on cross-platform builds of the AL compiler. Error

AL0670 Fast publishing failed because the RAD file has specified a non-existing
application object of type : '{0}' name: '{1}' ID: '{2}' to be added or modified.
Please do a full publishing before issuing a fast publishing again.

```
Error
```
AL0671 Fast publishing failed because the RAD file has specified an existing
application object of type: '{0}' name: '{1}' ID: '{2}' to be deleted. Please do a
full publishing before issuing a fast publishing again.

```
Error
```
AL0672 Filtering is only allowed on fields where FieldClass is set to Normal. Create a
Filter column and specify the filter by using the 'ColumnFilter' property.

```
Error
```
AL0673 The property '{0}' is required. Error

AL0674 The property '{0}' is required when property '{1}' is set to '{2}'. Error

AL0675 An implementation for the interface '{0}' is already specified in this list. Error

AL0676 The member '{0}' in object '{1}' cannot be declared as protected in object Error


**Id Message Default
Severity**
type '{2}'.

AL0677 The member '{0}' in object '{1}' cannot be declared as protected in object
type '{2}'.

```
Warning
(Future Error)
```
AL0678 The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
extension '{5}'. Choose another name for one of them. Otherwise, this might
cause runtime issues.

```
Information
```
AL0679 The application object '{0}' is not included in any entitlement and will
therefore not be accessible in the cloud.

```
Warning
```
AL0680 Cannot use addBefore or addAfter on a top-level data item. The anchor {0}
is a top level data item.

```
Error
```
AL0681 A DataItem with name '{0}' could not be found in the target {1}. Error

AL0682 A DataItem or Column with name '{0}' could not be found in the target {1}. Error

AL0683 The permissionset '{0}' belongs to a different module and cannot be used
when defining entitlements.

```
Error
```
AL0684 The permissionset '{0}' contains permissionsets or permission for objects
from other module. Permissions on objects from other modules will be
ignored.

```
Warning
```
AL0685 The length '{0}' of the calculation formula's target field '{1}' is greater than
the length '{2}' of the source flow field '{3}'. This could result in a runtime
error. Please make sure that the target field's length is less than equal to the
source field length.

```
Warning
(Future Error)
```
AL0686 The base type already defines a method called '{0}' with the same parameter
types.

```
Error
```
AL0687 The key '{0}' on table '{1}' cannot contain the fields defined for the primary
key in the IncludeFields property.

```
Error
```
AL0688 The key '{0}' on table '{1}' cannot contain the fields defined for the key in the
IncludeFields property.

```
Error
```
AL0689 The key '{0}' on table '{1}' cannot contain the fields defined for the SqlIndex
in the IncludeFields property.

```
Error
```
AL0690 The primary key '{0}' on table '{1}' (the first one in the key list) must not have
the IncludedFields property set.

```
Error
```
AL0691 The primary key '{0}' on table '{1}' cannot be obsolete. All related properties
will have no effect.

```
Error
```

**Id Message Default
Severity**

AL0692 The primary key '{0}' on table '{1}' cannot be obsolete. All related properties
will have no effect.

```
Warning
(Future Error)
```
AL0693 The field '{0}' which is part of the primary key of table '{1}' cannot be
obsolete. All related properties will have no effect.

```
Error
```
AL0694 The field '{0}' which is part of the primary key of table '{1}' cannot be
obsolete. All related properties will have no effect.

```
Warning
(Future Error)
```
AL0695 The method {0} will only be available for {1} development for runtime
version {2}.

```
Warning
(Future Error)
```
AL0696 Argument {0}: The argument should be a valid Field type. Error

AL0697 Argument {0}: The argument should be a valid Field type. Warning
(Future Error)

AL0698 Type {0} cannot be used in a 'case' statement. Error

AL0699 The symbol '{0}' cannot be referenced in this context. You can only reference
symbols from the base object '{1}', from extension objects defined in this
app with an ID lower or equal to '{2}', or from extension objects defined in
dependencies.

```
Error
```
AL0700 Dependency '{0}' must be referenced in the property '{1}' rather than as an
explicit dependency.

```
Warning
(Future Error)
```
AL0701 Dependency '{0}' must be referenced in the property '{1}' rather than as an
explicit dependency.

```
Error
```
AL0702 Dependency '{0}' is referenced in the property '{1}' and as an explicit
dependency. Remove the explicit dependency.

```
Warning
(Future Error)
```
AL0703 Dependency '{0}' is referenced in the property '{1}' and as an explicit
dependency. Remove the explicit dependency.

```
Error
```
AL0704 A layout must be specified through the 'ExcelLayout' property when the
default layout type for a report is 'Excel'.

```
Error
```
AL0705 Another layout with name '{0}' already exists. Error

AL0706 The property '{0}' cannot be used while also specifying the rendering
section.

```
Error
```
AL0707 Layouts of type '{0}' must specify a LayoutFile with one of the following
extensions: {1}.

```
Error
```
AL0708 MimeType values must be less than {0} characters in length. Error


**Id Message Default
Severity**

AL0709 The layout file at path '{0}' specified in layout '{1}' in {2} {3} does not exist. Error

AL0710 The DefaultRenderingLayout property can only be used with layouts
specified in the report's rendering section.

```
Error
```
AL0711 A member of type {0} with name '{1}' is already defined in {2} '{3}' by the
extension '{4}'. Duplicate member names are not allowed when defining
CueActions.

```
Warning
(Future Error)
```
AL0712 A member of type {0} with name '{1}' is already defined in {2} '{3}' by the
extension '{4}'. Duplicate member names are not allowed when defining
CueActions.

```
Error
```
AL0713 Events in control add-ins should be implemented as triggers. Error

AL0714 The name '{0}' is an Area type. Using an Area type name will limit
extensibility as dependent extension won't be able to reference it.

```
Error
```
AL0715 The {0} name '{1}' is reserved for future AL language features. Warning
(Future Error)

AL0716 The {0} name '{1}' is reserved for future AL language features. Error

AL0717 The property 'CalcFormula' is required for the field '{0}' in {1} '{2}' because
the field's property 'FieldClass' is set to 'FlowField'.

```
Warning
```
AL0718 Report layouts must have a name. Error

AL0719 Argument {0}: The argument should be a valid Field type. An argument of
type Joker or Variant might have an underlying type that is not a valid Field
type.

```
Information
```
AL0720 An application object '{0} {1}' could not be found in the current extension.
Only application objects that belong to the current extensions can be used
in this context.

```
Error
```
AL0721 Reports that use the rendering syntax must also define the
DefaultRenderingLayout property.

```
Error
```
AL0722 The property '{0}' is not allowed on {1} '{2}' because the {3} '{4}' is using the
ActionRef syntax or the app.json specifies the
'NoPromotedActionProperties' feature.

```
Error
```
AL0723 The {0} '{1}' cannot be used as target of the ActionRef '{2}'. ActionRefs can
only target Actions.

```
Error
```
AL0724 An area of type '{0}' is not valid on pages of type '{1}'. Error

AL0725 The action type '{0}' is not allowed in area '{1}'. Error


**Id Message Default
Severity**

AL0726 An identifier, a literal, or an option access is expected as the value of a filter
expression.

```
Error
```
AL0727 The {0} '{1}' can only be used if the property '{2}' is set. Warning
(Future Error)

AL0728 The {0} '{1}' can only be used if the property '{2}' is set to '{3}'. Warning
(Future Error)

AL0729 The {0} '{1}' can only be used if the property '{2}' is set with any of the values
of: '{3}'.

```
Warning
(Future Error)
```
AL0730 The field '{0}' cannot be used in a sum index. Error

AL0731 The name '{0}' does not exist in the current context. Warning
(Future Error)

AL0732 Access modifier '{0}' is not allowed for member '{1}' in the context of object
type '{2}'.

```
Error
```
AL0733 Access modifier '{0}' is not allowed for member '{1}' in the context of object
type '{2}'.

```
Warning
(Future Error)
```
AL0734 The value '{0}' of the property '{1}' is not a valid GUID. Error

AL0735 The custom action '{0}' cannot be defined in {1} '{2}' because '{2}' uses
promoted action properties. Convert the promoted properties into
ActionRefs in oder to use custom actions.

```
Error
```
AL0736 The value '{0}' of the property 'FlowEnvironmentId' is not a valid. It must
either be a GUID or must match the pattern 'Default-'.

```
Error
```
AL0737 The {0} '{1}' cannot be referenced in {2} '{3}' because '{1}' is defined in the
promoted part of the action part while '{3}' uses promoted action
properties.

```
Error
```
AL0738 The name of {0} '{1}' cannot be empty. Error

AL0739 The name of {0} '{1}' cannot be empty. Warning

AL0740 The permission set '{0}' cannot be excluded and included in the same
permission set.

```
Error
```
AL0741 The permission set '{0}' cannot exclude itself. Error

AL0742 The property '{0}' is not valid for action '{1}' defined in control '{2}' of type
'{3}'.

```
Error
```
AL0743 The property '{0}' is not valid for action '{1}' defined in control '{2}' of type Warning


**Id Message Default
Severity**
'{3}'. (Future Error)

AL0744 The property '{0}' is not valid for action '{1}' defined in a report request
page.

```
Error
```
AL0745 The property '{0}' is not valid for action '{1}' defined in a report request
page.

```
Warning
(Future Error)
```
AL0746 The auto-increment field '{0}' has already been defined for table '{1}'. Error

AL0747 The data type on the '{0}' control is not valid for this ExtendedDataType
value. Valid data types are BigText and Text without max size.

```
Error
```
AL0748 The return type '{0}' of the {1} method '{2}' has 'Internal' accessibility. The
return value will not be usable outside of this module without an implicit
conversion.

```
Warning
```
AL0749 The type '{0}' of the parameter '{1}' of the {2} method '{3}' has 'Internal'
accessibility. The method will not be callable outside of this module without
an implicit conversion.

```
Warning
```
AL0750 Enum values can't be nested. Use '{0}' instead. Error

AL0751 Enum values can't be nested. Use '{0}' instead. Warning
(Future Error)

AL0752 The name of a dataitem cannot be empty because it can cause runtime
errors.

```
Error
```
AL0753 The name of a dataitem cannot be empty because it can cause runtime
errors.

```
Warning
(Future Error)
```
AL0754 The '{0}' already defines a built-in member called '{1}'. Choose another name
for {2} '{1}', or it might cause runtime issues.

```
Error
```
AL0755 The '{0}' already defines a built-in member called '{1}'. Choose another name
for {2} '{1}', or it might cause runtime issues.

```
Warning
(Future Error)
```
AL0756 The division by Abs(integer) will change its behavior in release version 11.
For more information visit the official documentation.

```
Warning
```
AL0757 The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
extension '{5}'. Choose another name for one of them. Otherwise, this might
cause runtime issues.

```
Error
```
AL0758 The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
extension '{5}'. Choose another name for one of them. Otherwise, this might
cause runtime issues.

```
Warning
(Future Error)
```

**Id Message Default
Severity**

AL0759 The value '{0}' specified for FormatRegion cannot be parsed as a valid
format culture name.

```
Error
```
AL0760 The value '{0}' specified for FormatRegion is not a standard format culture
name.

```
Error
```
AL0761 An incorrect value was used for the category. One of the values of the enum
{0} {1} is expected which is available in platform version {2} and higher.

```
Error
```
AL0762 Length of the argument '{0}' cannot exceed {1} characters. Error

AL0763 {0} can contain only underscores and alphanumeric characters. Error

AL0764 {0} cannot be empty. Error

AL0765 An argument of type {0} cannot be used in an External Business Event. Error

AL0766 An External Business Event with {0} {1} and version {2} is already declared. Error

AL0767 The URL '{0}' cannot be used as the ruleset path for this project because its
configuration does not permit external rulesets.

```
Error
```
AL0768 The property '{0}' is required when property '{1}' is set to '{2}'. Warning
(Future Error)

AL0769 The property '{0}' is required. Warning
(Future Error)

AL0772 The attribute '{0}' can only be used in combination with attribute '{1}'. Error

AL0773 The number of files found in '{0}' exceeds {1}. This may result in a slower
compilation.

```
Warning
```
AL0774 Try methods should not specify an explicit return value, because the value
will be discarded. The actual return value depends on whether the method
returns an error or not.

```
Error
```
AL0775 Try methods should not specify an explicit return value, because the value
will be discarded. The actual return value depends on whether the method
returns an error or not.

```
Warning
(Future Error)
```
AL0776 The identifier '{0}' is not a valid permission value. Error

AL0777 The implicit conversion will overflow when converting from a 'Guid' to a '{0}'
which is shorter than the converted textual representation of a 'Guid'.

```
Error
```
AL0778 The implicit conversion will overflow when converting from a 'Guid' to a '{0}'
which is shorter than the converted textual representation of a 'Guid'.

```
Warning
(Future Error)
```

**Id Message Default
Severity**

AL0779 It is not allowed to assign a value to a field of FieldClass='{0}'. Error

AL0780 It is not allowed to assign a value to a field of FieldClass='{0}'. Warning
(Future Error)

AL0781 Cannot find a reference of DataItem with name '{0}'. Error

AL0782 A page extension is only allowed to access control add-ins defined within its
own extension scope.

```
Warning
(Future Error)
```
AL0783 A page extension is only allowed to access control add-ins defined within its
own extension scope.

```
Error
```
AL0784 The version number '{0}' for the argument '{1}' does not match the expected
format: X.Y where X and Y represent positive integers.

```
Error
```
AL0785 The control with name '{0}' cannot be declared in the page customization
'{1}' targeting page '{2}' because controls of type '{3}' are not supported in
page customizations.

```
Error
```
AL0786 The property '{0}' cannot be specified on the control '{1}' in the page
customization '{2}' targeting page '{3}', because this property type is not
supported in page customizations.

```
Error
```
AL0787 The control with name '{0}' cannot be declared in the page customization
'{1}' targeting page '{2}' because it is not using a source table field as source
expression.

```
Error
```
AL0788 An area of type '{0}' is only valid on pages of type(s) '{1}'. Warning
(Future Error)

AL0789 Using directives are ignored if a namespace is not specified. Warning

AL0790 The using directive for '{0}' appeared previously in this namespace
declaration.

```
Warning
```
AL0791 The namespace '{0}' is unknown. Error

AL0792 Unused using directive '{0}'. Hidden

AL0793 The property '{0}' cannot be used on a multi-select action with '{1}' scope. Error

AL0794 The value '{0}' for property '{1}' is not valid for action '{2}' defined in control
'{3}' of type '{4}'.

```
Error
```
AL0795 The parameter '{0}' cannot be of type 'SecretText'. Error

AL0796 The 'Unwrap' method should only be used inside a non-debuggable
method otherwise the contents of the value will be viewable through the

```
Warning
```

**Id Message Default
Severity**
debugger.

AL0797 {0} '{1}' is moved. {2}. Error

AL0798 Currently, the Moved(To/From) property is exclusively accessible to
Microsoft and select publishers.

```
Error
```
AL0799 The field with ID '{0}' and name '{1}' cannot be used as source expression in
the page customization '{2}' targeting page '{3}'.

```
Error
```
AL0800 The field '{0}' specifies ExtendedDataType '{1}'. This ExtendedDataType can
only be set on a control.

```
Error
```
AL0801 {0} '{1}' is marked to be moved. {2}. Warning

AL0802 The parameter '{0}' cannot be of type 'SecretText'. Error

AL0803 The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
extension '{5}'. Choose another name for one of them. Otherwise, this might
cause runtime issues.

```
Warning
(Future Error)
```
AL0804 You cannot reference the {0} '{1}' because it is defined in the page
customization '{2}'.

```
Warning
(Future Error)
```
AL0805 The object ID '{0}' should not be surrounded with quotes. Warning
(Future Error)

AL0806 The object ID '{0}' should not be surrounded with quotes. Error

AL0807 The integer '{0}' should not be used as the name for the object. Warning

AL0808 You cannot set the '{0}' property to '{1}' for {2} '{3}' in the page
customization '{4}'.

```
Error
```
AL0809 The variable '{0}' is not allowed to be of type 'SecretText' because it is
declared as protected.

```
Error
```
AL0810 The name '{0}' cannot be used for a system action. The allowed names in a
'{1}' page are: '{2}'.

```
Error
```
AL0811 The trigger '{0}' cannot be defined on the system action named '{1}' in a
page of type '{2}'.

```
Error
```
AL0812 The control '{0}' cannot be declared in the 'PromptOptions' area because it
is not a page field of type 'Option'.

```
Error
```
AL0813 The property '{0}' can only be specified when the property '{1}' has a value
of '{2}' if the runtime version is '{3}' or higher.

```
Error
```

**Id Message Default
Severity**

AL0814 The source of a column cannot be a flow filter. Warning
(Future Error)

AL0815 The source of a column cannot be a flow filter. Error

AL0816 The property '{0}' cannot be set if the property '{1}' is set to '{2}'. Warning
(Future Error)

AL0817 Controls of type '{0}' are not allowed in the '{1}' area for pages of type '{2}'. Error

AL0818 The {0} '{1}' already defines an event called '{2}' with the same parameter
types in '{3}'.

```
Warning
(Future Error)
```
AL0819 The {0} '{1}' already defines an event called '{2}' with the same parameter
types in '{3}'.

```
Error
```
AL0820 {0} '{1}' is missing. Warning

AL0821 The method '{0}' is missing or does not have exactly one parameter of type
{1}.

```
Warning
```
AL0822 '{0}' is an ambiguous reference between '{1}' defined by the extension '{2}'
and '{3}' defined by the extension '{4}'.

```
Warning
```
AL0823 Field '{0}' is marked as PendingMove and cannot be used in an active key. Warning

AL0824 Field '{0}' is moved and cannot be used in an active key. Error

AL0825 Field '{0}' cannot be moved to {1} '{2}' because '{2}' is marked as Moved. Error

AL0826 The type '{0}' cannot be used as a type argument in this context. Warning
(Future Error)

AL0827 Argument {0}: The argument {0} of field class {1} is not supported. Allowed
field class types are '{2}'.

```
Error
```
AL0828 The field '{0}' with ID '{1}' can't be moved because it is part of the table's
primary key.

```
Error
```
AL0829 Symbol of kind {0} '{1}' cannot be moved to its own app. Error

AL0830 The method '{0}' is not supported as the implementation for the interface
method because it is a try function.

```
Warning
(Future Error)
```
AL0831 The method '{0}' is not supported as the implementation for the interface
method because it is a try function.

```
Error
```
AL0832 Action area of type '{0}' is not valid in control '{1}' of type '{2}'. Error


**Id Message Default
Severity**

AL0833 {0} '{1}' cannot be defined outside an action area or group on this control
type.

```
Error
```
AL0834 'MovedTo' property is required for a symbol of kind '{0}' {1} that has
ObsoleteState set to Moved or PendingMove.

```
Error
```
AL0835 The LayoutFile '{0}' is already being used. To avoid build issues, a layout file
shouldn't be updated by different layouts.

```
Warning
```
AL0836 The {0} '{1}' contains a reference to the field '{2}' which is defined in another
object from the same app. If you are preparing to move this object to
another extension in the future, this reference will be an issue.

```
Warning
```
AL0837 The symbol '{0}' results in the same translation ID as one or more other
symbols. Rename symbol to resolve the problem.

```
Warning
(Future Error)
```
AL0838 The XLIFF file for text data could not be generated. Error

AL0839 The symbol '{0}' has same trans unit ID in Text Data XLIFF file as one or more
other symbols.

```
Error
```
AL0840 The file extension '{0}' is not valid. Example of an expected value is '.app'. Error

AL0841 The file extension '{0}' is already defined. Error

AL0842 The type '{0}' of the {1} field '{2}' has 'Internal' accessibility. The field will not
be usable outside of this module without an implicit conversion.

```
Warning
```
AL0843 The property '{0}' can only be used if the {1}'s type is '{2}'. Error

AL0844 The property '{0}' can only be used if the {1}'s type is one of these values:
'{2}'.

```
Error
```
AL0845 The {0} '{1}' is already being used. The EntityName and EntityNames
property values must be unique.

```
Warning
(Future Error)
```
AL0846 The {0} '{1}' is already being used. The EntityName and EntityNames
property values must be unique.

```
Error
```
AL0847 '{0}' does not contain a definition for '{1}'. Error

AL0848 '{0}' is a keyword from version '{1}'. Warning

AL0999 Internal error: {0}. Error

AL1000 Ignoring /noconfig option because it was specified in a response file. Warning

AL1001 Source file '{0}' could not be found. Error


**Id Message Default
Severity**

AL1002 Error opening response file '{0}'. Error

AL1003 An instance of analyzer {0} cannot be created from {1} : {2}. Warning

AL1004 The assembly {0} does not contain any analyzers. Warning

AL1005 Unable to load Analyzer assembly {0} : {1}. Warning

AL1006 Metadata file '{0}' could not be found. Error

AL1007 Missing file specification for '{0}' option. Error

AL1008 Command-line syntax error: Missing '{0}' for '{1}' option. Error

AL1009 Unrecognized option: '{0}'. Error

AL1010 Command-line syntax error: Missing :<number> for '{0}' option. Error

AL1011 Source file '{0}' specified multiple times. Warning

AL1012 Could not write to output file '{0}' -- '{1}'. Error

AL1013 '{0}' is a binary file instead of a text file. Error

AL1014 Source file '{0}' could not be opened -- {1}. Error

AL1015 Compilation canceled by user. Error

AL1017 The manifest file is not valid. {0}. Error

AL1018 Directory '{0}' could not be found. Error

AL1019 One or more dependencies defined in the project manifest are not valid.
One or more of the required attributes: 'publisher', 'name', 'version', and 'id'
are either missing or not valid.

```
Error
```
AL1021 The package cache path has not been specified. Error

AL1022 A package with publisher '{0}', name '{1}', and a version compatible with '{2}'
could not be found in the package cache folders: {3}.

```
Error
```
AL1023 The package file {0} is not valid. Error

AL1024 A package with publisher '{0}', name '{1}', and a version compatible with '{2}'
could not be loaded. {3}.

```
Error
```
AL1025 The file at location '{0}' does not match any definition. Warning

AL1026 A warning occurred during XML validation: '{0}'. Warning


**Id Message Default
Severity**

AL1028 An IO exception has happened when trying to write to output file '{0}' --
'{1}'.

```
Error
```
AL1029 Translation file '{0}' has invalid target language '{1}'. Warning

AL1030 Translation file '{0}' is missing a target language. Warning

AL1031 Successfully included translations for: {0}. Information

AL1032 Translation file '{0}' has the same target language as another translation file. Error

AL1033 An error occurred while loading the included rule set file {0} - {1}. Error

AL1034 The link '{0}' must contain a placeholder with value 0 for the user locale. Error

AL1035 The manifest properties 'baseHelpUrl' and 'supportedLocales' must both be
specified and have values.

```
Error
```
AL1036 The locale '{0}' is not valid. Error

AL1037 The locale '{0}' is already defined. Error

AL1038 The version number '{0}' for the property '{1}' does not match the expected
format: W.X.Y.Z where W, X, Y, and Z represent positive integers.

```
Error
```
AL1039 The version number '{0}' for the property '{1}' does not match the expected
format: X.Y where X and Y represent positive integers.

```
Error
```
AL1040 The guid number '{0}' does not match the expected pattern: "^[0-9a-fA-F]
{{8}}-[0-9a-fA-F]{{4}}-[0-9a-fA-F]{{4}}-[0-9a-fA-F]{{4}}-[0-9a-fA-F]{{12}}$".

```
Error
```
AL1041 The property '{0}' must be defined in the manifest. Error

AL1042 The id '{0}' for the package with publisher '{1}', name '{2}', and version '{3}'
specified in the project manifest does not match the id '{4}' of the package
with the same name, publisher, and version found in the package cache
folder.

```
Error
```
AL1043 The runtime version '{0}' is not supported by the AL compiler. Error

AL1044 The value for the manifest property '{0}' is not valid. Expected type: {1}. Error

AL1045 The package cache {0} could not be found. Error

AL1046 The application ID ranges {0} are overlapping. Error

AL1047 The application ID range {0} is not valid. Error

AL1048 Both 'idRange' and 'idRanges' properties are added. You should use the
'idRanges' property and remove the 'idRange' property.

```
Error
```

**Id Message Default
Severity**

AL1049 A project without a manifest must have the /out option specified. Error

AL1050 Fast publishing requires an application file '{0}' to be build and published. Error

AL1051 Fast publishing requires that there are no manifest changes for the
application '{0}'.

```
Error
```
AL1052 The link '{0}' can only contain one placeholder with value 0 for the user
locale. No other placeholder values are allowed.

```
Error
```
AL1053 The value '{0}' is not valid for the manifest property '{1}'. Error

AL1054 Invalid reference module: {0}. Please clear the downloaded symbols cache
and re-download symbols.

```
Error
```
AL1055 Invalid reference module: {0}. Please clear the downloaded symbols cache
and re-download symbols.

```
Warning
```
AL1056 A package with publisher '{0}', name '{1}', and a version compatible with '{2}'
could not be loaded. {3}.

```
Warning
```
AL1057 The module specification is not valid. One or more of the required
attributes: 'publisher', 'name', and 'id' are either missing or not valid.

```
Error
```
AL1058 appId and Id are both specified for a dependency property. The appId value
will be ignored.

```
Warning
```
AL1059 Feature '{0}' can only be enabled, if feature '{1}' is also enabled. Warning

AL1060 The max degree of parallelism must be -1 or positive. Error

AL1061 An error occurred during file validation: '{0}'. Error

AL1062 Too many key vault URLs specified. Error

AL1063 Key vault URL is too long. Error

AL1064 Key vault URL is not a valid Azure key vault URL. A valid key vault URL must
use HTTPS and point to the Azure key vault domain.

```
Error
```
AL1065 Key vault URL should not have a path or query string. Error

AL1066 Duplicate package dependency with application ID '{0}', publisher '{1}', and
name '{2}'. Remove duplicate dependencies in the application manifest.

```
Error
```
AL1067 Duplicate package dependency with publisher '{0}', and name '{1}'. Remove
duplicate dependencies in the application manifest.

```
Error
```
AL1068 Duplicate package dependency with application ID '{0}', and publisher '{1}'. Error


**Id Message Default
Severity**
Remove duplicate dependencies in the application manifest.

AL1069 Duplicate package dependency with application ID '{0}', and name '{1}'.
Remove duplicate dependencies in the application manifest.

```
Error
```
AL1070 Duplicate package dependency with application ID '{0}'. Remove duplicate
dependencies in the application manifest.

```
Error
```
AL1071 Error writing to XML documentation file: {0}. Error

AL1072 The name for the preprocessing symbol is not valid; '{0}' is not a valid
identifier.

```
Warning
```
AL1073 The procedure with name {0} has the same name as a declared trigger. Error

AL1074 Both 'applicationInsightsKey' and 'applicationInsightsConnectionString' are
added. You should use the 'applicationInsightsConnectionString' property
and remove the 'applicationInsightsKey' property.

```
Error
```
AL1075 Both 'ShowMyCode' and 'ResourceExposurePolicy' properties are added.
You should use the 'ResourceExposurePolicy' property and remove the
'ShowMyCode' property.

```
Error
```
AL1076 A package that satisfies the dependency on app with ID {0} with name '{1}'
and publisher '{2}' was found, but the name or publisher has changed. New
name '{3}' and new publisher '{4}'. Consider updating the dependency
reference to the new name/publisher.

```
Information
```
AL1077 An error was encountered when trying to load the workspace: {0}. Error

AL1078 Key vault URL is not a valid Azure key vault URL. A valid key vault URL must
use HTTPS and point to the Azure key vault domain.

```
Warning
(Future Error)
```
AL1079 Debugging will not work for this extension because 'allowDebugging' has
been set to false and 'applyToDevExtension' to true.

```
Information
```
AL1080 Source will still be visible for this extension via debugging because
'allowDebugging' has been set to true.

```
Information
```
AL1081 Unable to update report layout '{0}' for '{1}'. Reason: {2}. Error

AL1082 The manifest property '{0}' is only available for Target '{1}'. Error

AL1100 File name '{0}' is empty, contains invalid characters, has a drive specification
without an absolute path, or is too long.

```
Fatal Error
```
AL1101 Target must specify one of: 'internal', 'solution', 'extension'. Fatal Error

AL1130 The format of property '{0}' must be a timeout duration specified as
'[d.]hh:mm:ss[.fffffff]'.

```
Error
```

**Id Message Default
Severity**

AL1150 The link in parameter '{0}' ({1}) is not valid. {2}. Error

AL1151 Cannot create a manifest for Extension "{0}" because the Name and
Publisher match the current application. Remove this dependency from the
application manifest.

```
Error
```
AL1152 Dependency with ID '{0}' matches the current application ID. Remove this
dependency from the application manifest.

```
Error
```
AL1153 The referenced module '{1}' with runtime reference version '{0}' cannot be
loaded by the compiler with version '{2}'.

```
Error
```
AL1154 It is not possible to specify both '{0}' and '{1}' at the same time. Error

AL1155 Missing folder specification for '{0}' option. Error

AL1156 Comments are not recommended inside the manifest file as they can cause
interoperability issues with CI/CD pipelines or other integrations.

```
Warning
```
AL1401 Reference '{0}' in application object '{1}' does not exist. Designer
Customization
Warning

AL1402 {0} '{1}' is missing. Designer
Customization
Warning

AL1403 '{0}' is an ambiguous reference between '{1}' defined by the extension '{2}'
and '{3}' defined by the extension '{4}'.

```
Designer
Customization
Warning
```
AL1404 The action '{0}' is not found in the target '{1}'. Designer
Customization
Warning

AL1405 The control '{0}' is not found in the target '{1}'. Designer
Customization
Warning

AL1406 The view '{0}' is not found in the target '{1}'. Designer
Customization
Warning

AL1407 At least one target has to be specified for the move. Designer
Customization
Warning

AL1408 Invalid application object identifier. A number or an application object name
is expected.

```
Designer
Customization
```

**Id Message Default
Severity**
Warning

AL1409 Page '{0}' should be of type 'RoleCenter'. Designer
Customization
Warning

AL1410 The target {0} '{1}' for the extension object is not found. Designer
Customization
Warning

AL1411 Multiple page customizations have been specified for the same page {0}
within the same profile.

```
Designer
Customization
Warning
```
AL1412 {0} '{1}' is marked for removal. {2}. Designer
Customization
Warning

AL1413 A member of type {0} with name '{1}' is already defined in {2} '{3}' by the
extension '{4}'.

```
Designer
Customization
Warning
```
AL1414 The page customization for page '{0}' does not make any modifications, so it
can be removed without affecting any profiles or user personalization.

```
Designer
Customization
Information
```
AL1415 {0} '{1}' is removed. {2}. Designer
Customization
Warning

AL1416 The {0} '{1}' cannot be moved relatively to '{2}' because '{2}' is missing. This
move is ignored.

```
Designer
Customization
Information
```
AL1417 The {0} '{1}' cannot be added relatively to '{2}' because '{2}' is missing. '{1}' is
added at a default location instead.

```
Designer
Customization
Information
```
AL1418 A DataItem with name '{0}' could not be found in the target {1}. Designer
Customization
Warning

AL1419 A DataItem or Column with name '{0}' could not be found in the target {1}. Designer
Customization
Warning

AL1420 The {0} '{1}' cannot be used as target of the ActionRef '{2}'. ActionRefs can
only target Actions. Ignoring the ActionRef.

```
Designer
Customization
Warning
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Id Message Default
Severity
AL1421 The {0} '{1}' is using the '{2}' property. This will be automatically converted to
the new syntax when customizing the related page in the webclient.
```
```
Designer
Customization
Warning
AL1422 The target action '{0}' cannot be resolved in page '{1}'. Ignoring the
ActionRef.
```
```
Designer
Customization
Warning
AL1423 '{0}' does not contain a definition for '{1}'. Designer
Customization
Warning
AL1424 The name '{0}' does not exist in the current context. Designer
Customization
Warning
AL1425 The field with ID '{0}' and name '{1}' cannot be used as source expression in
the page customization '{2}' targeting page '{3}'. Ignoring the page field.
```
```
Designer
Customization
Warning
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# Warnings Turning into Errors Overview

Article•05/14/2024

This topic lists all the warning diagnostics that will turn or have turned into an error in
the specified Business Central release.

```
Release Diagnostics Message
2025
release
wave 1
```
- AL0755
- AL0803
- AL0816
- AL0818
- AL0826
- AL0837
- AL0845
    - The '{0}' already defines a built-in member called '{1}'. Choose
    another name for {2} '{1}', or it might cause runtime issues.
    - The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
    extension '{5}'. Choose another name for one of them. Otherwise,
    this might cause runtime issues.
    - The property '{0}' cannot be set if the property '{1}' is set to '{2}'.
    - The {0} '{1}' already defines an event called '{2}' with the same
    parameter types in '{3}'.
    - The type '{0}' cannot be used as a type argument in this context.
    - The symbol '{0}' results in the same translation ID as one or more
    other symbols. Rename symbol to resolve the problem.
    - The {0} '{1}' is already being used. The EntityName and
    EntityNames property values must be unique.

```
2024
release
wave 2
```
- AL0545
- AL0775
- AL0778
- AL0780
- AL0788
- AL0804
- AL0805
- AL0814
- AL0830
    - An area of type '{0}' is not valid on pages of type '{1}'.
    - Try methods should not specify an explicit return value, because
    the value will be discarded. The actual return value depends on
    whether the method returns an error or not.
    - The implicit conversion will overflow when converting from a 'Guid'
    to a '{0}' which is shorter than the converted textual representation
    of a 'Guid'.
    - It is not allowed to assign a value to a field of FieldClass='{0}'.
    - An area of type '{0}' is only valid on pages of type(s) '{1}'.
    - You cannot reference the {0} '{1}' because it is defined in the page
    customization '{2}'.
    - The object ID '{0}' should not be surrounded with quotes.
    - The source of a column cannot be a flow filter.
    - The method '{0}' is not supported as the implementation for the
    interface method because it is a try function.

```
2024
release
wave 1
```
- AL0700
- AL0702
- AL0751
- AL0753
- AL0758
- AL0782
    - Dependency '{0}' must be referenced in the property '{1}' rather
    than as an explicit dependency.
    - Dependency '{0}' is referenced in the property '{1}' and as an
    explicit dependency. Remove the explicit dependency.
    - Enum values can't be nested. Use '{0}' instead.
    - The name of a dataitem cannot be empty because it can cause
    runtime errors.

```
ﾉ Expand table
```

```
Release Diagnostics Message
```
- The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the
extension '{5}'. Choose another name for one of them. Otherwise,
this might cause runtime issues.
- A page extension is only allowed to access control add-ins defined
within its own extension scope.

```
2023
release
wave 2
```
- AL0731
- AL0733
- AL0743
- AL0745
- AL1078
    - The name '{0}' does not exist in the current context.
    - Access modifier '{0}' is not allowed for member '{1}' in the context
    of object type '{2}'.
    - The property '{0}' is not valid for action '{1}' defined in control '{2}'
    of type '{3}'.
    - The property '{0}' is not valid for action '{1}' defined in a report
    request page.
    - Key vault URL is not a valid Azure key vault URL. A valid key vault
    URL must use HTTPS and point to the Azure key vault domain.
2023
release
wave 1
- AL0711 - A member of type {0} with name '{1}' is already defined in {2} '{3}'
by the extension '{4}'. Duplicate member names are not allowed
when defining CueActions.
2022
release
wave 2
- AL0660
- AL0677
- AL0715
- The property '{0}' cannot be customized.
- The member '{0}' in object '{1}' cannot be declared as protected in
object type '{2}'.
- The {0} name '{1}' is reserved for future AL language features.
2022
release
wave 1
- AL0692
- AL0694
- The primary key '{0}' on table '{1}' cannot be obsolete. All related
properties will have no effect.
- The field '{0}' which is part of the primary key of table '{1}' cannot
be obsolete. All related properties will have no effect.

```
2021
release
wave 2
```
- AL0613 - Wrong signature. Correct signature for '{0}' is '{1}'.

```
2021
release
wave 1
```
- AL0639 - 'Variant' is not a valid column type for column '{0}' in report '{1}'.

```
2020
release
wave 1
```
- AL0559 - A Part type page cannot contain other parts.

Get Started with AL
Developing Extensions

### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0100

Article•11/25/2024

Unterminated multiline comment.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0101

Article•11/25/2024

Constant value '{0}' is outside the range for a Decimal.

Constant value '11212211221234123465676343434435435343232.12' is outside the
range for a Decimal

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0102

Article•11/25/2024

Constant value '{0}' is outside the range for a BigInteger.

Constant value '3000000000000000000000L' is outside the range for a BigInteger

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0103

Article•11/25/2024

Constant value '{0}' is outside the range for an Integer.

Constant value '3000000000' is outside the range for an Integer

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0104

Article•11/25/2024

Syntax error, '{0}' expected.

Syntax error, ';' expected

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0105

Article•11/25/2024

Syntax error, identifier expected; '{1}' is a keyword.

Syntax error, identifier expected; 'true' is a keyword

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0106

Article•11/25/2024

Syntax error, 'TO' or 'DOWNTO' expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0107

Article•11/25/2024

Syntax error, identifier expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0108

Article•11/25/2024

Indexers must have at least one value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0109

Article•11/25/2024

Unexpected token.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0110

Article•11/25/2024

Orphaned ELSE statement. This is most likely because of an unnecessary semicolon
placed just before the ELSE keyword.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0111

Article•11/25/2024

Semicolon expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0112

Article•11/25/2024

{0} is not a valid attribute.

The specified attribute is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0113

Article•11/25/2024

At least one dimension must be specified.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0114

Article•11/25/2024

Syntax error, integer literal expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0115

Article•11/25/2024

Object type expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0116

Article•11/25/2024

Invalid value for '{0}'. Allowed values are '{1}'.

Invalid value for 'PageType'. Allowed values are
'Card,List,RoleCenter,CardPart,ListPart,Document,Worksheet,ListPlus,ConfirmationDialog,.
..'

The value defined for the property is not valid. Refer to the property's documentation to
see the allowed values.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Error message example

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0117

Article•11/25/2024

Illegal statement. Only assignment and method invocation can be used as a statement.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0118

Article•11/25/2024

The name '{0}' does not exist in the current context.

The referenced name does not exist in the current context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0119

Article•11/25/2024

The parameter name '{0}' is already defined.

Multiple parameters with the same name are defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0120

Article•11/25/2024

A local or parameter named '{0}' cannot be declared in this scope because that name is
used in an enclosing local scope to define a local or parameter.

Cannot declare local or parameter in a scope if there already is a local or parameter with
the same name used in an enclosing local scope.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0121

Article•11/25/2024

The variable name '{0}' is already defined.

Multiple variables with the same name are defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0122

Article•11/25/2024

Cannot implicitly convert type '{0}' to '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0123

Article•11/25/2024

The return value name '{0}' is already defined.

Multiple return values with the same name are defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0124

Article•11/25/2024

The property '{0}' cannot be used in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0125

Article•11/25/2024

Method name expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0126

Article•11/25/2024

No overload for method '{0}' takes {1} arguments. Candidates: {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0127

Article•11/25/2024

Member '{0}' cannot be used like a method.

The referenced member cannot be invoked like a method.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0128

Article•11/25/2024

Language identifier expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0129

Article•11/25/2024

The left-hand side of an assignment must be a variable or field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0130

Article•11/25/2024

A 'var' argument must be an assignable variable.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0131

Article•11/25/2024

The property CharAllowed must be specified in pairs of characters. The first character in
the pair must be equal to or less than the second.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0132

Article•11/25/2024

'{0}' does not contain a definition for '{1}'.

The referenced element does not contain a definition for the referenced member.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0133

Article•11/25/2024

Argument {0}: cannot convert from '{1}' to '{2}'.

The given argument has a type different from the one expected and cannot make the
conversion.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0134

Article•11/25/2024

'{0}' is not recognized as a valid type.

Unknown type. For more information about the data types available as part of the AL
Language, see Data Types and Methods in AL.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0135

Article•11/25/2024

There is no argument given that corresponds to the required formal parameter '{0}' of
'{1}'.

The referenced element is missing an argument for a required parameter.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0136

Article•11/25/2024

The loop variable in a 'for' statement must be a numeric type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0137

Article•11/25/2024

No enclosing loop out of which to break.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0138

Article•11/25/2024

The case expression cannot be an array.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0139

Article•11/25/2024

Since '{0}' doesn't have a return value, EXIT cannot be called with a value.

EXIT cannot be called with a value inside a procedure that doesn't have a return value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0140

Article•11/25/2024

The expression is not valid for the WITH statement.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0142

Article•11/25/2024

Only variables of type record can be marked as TEMPORARY.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0143

Article•11/25/2024

Cannot apply indexing with [] to an expression of type '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0144

Article•11/25/2024

Wrong number of indices inside []; expected {0}.

The number of indices inside [] does not match the dimensions of the array.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0145

Article•11/25/2024

Assignment is not valid for arrays.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0146

Article•11/25/2024

The maximum number of array elements is {0}. Actual number is {1}.

The number of elements in an array must not exceed 1000000.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0147

Article•11/25/2024

An array dimension must be a positive number.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0148

Article•11/25/2024

The table filter is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0149

Article•11/25/2024

There is an 'ELSE' statement without an 'IF' in property {0}.

An 'ELSE' statement must be preceeded by an 'IF'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0150

Article•11/25/2024

Invalid CONST expression. A valid integer or an identifier is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0151

Article•11/25/2024

Expression must be an Option.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0152

Article•11/25/2024

The value '{0}' is used more than once.

There is a duplicate option value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0153

Article•11/25/2024

The property '{0}' cannot be blank.

A property value cannot be blank.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0154

Article•11/25/2024

The maximum length for a field of type '{0}' is {1}.

The length of the given field exceeds the maximum length permitted for its type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0155

Article•11/25/2024

A member of type {0} with name '{1}' is already defined in {2} '{3}' by the extension '{4}'.

Multiple members with the same name are defined by the same or several extensions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0156

Article•11/25/2024

'{0}' is not a valid field type.

Non-valid field type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0157

Article•11/25/2024

'{0}' is not a valid variable type.

Non-valid variable type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0158

Article•11/25/2024

'{0}' is not a valid parameter type.

Non-valid parameter type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0159

Article•11/25/2024

'{0}' is not a valid return type.

Non-valid return type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0160

Article•11/25/2024

'{0}' is not a valid language identifier.

Non-valid language identifier.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0161

Article•11/25/2024

'{0}' is inaccessible due to its protection level.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0162

Article•11/25/2024

'{0}' is not a valid trigger.

The referenced trigger is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0163

Article•11/25/2024

Wrong signature. Correct signature for '{0}' is '{1}'.

The signature for the given trigger is wrong. For more information about the correct
signature, refer to the trigger's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0164

Article•11/25/2024

The trigger '{0}' is already defined.

There is a duplicate trigger defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0165

Article•11/25/2024

Triggers cannot be called directly.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0166

Article•11/25/2024

Argument {0}: must be a member.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0167

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set with any of the values of: '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0168

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

# Compiler Error AL0169

Article•11/25/2024

The option value '{0}' is not valid.

Non-valid option value.

```
AL
```
Setting the ObsoleteState to Removed for an enum will throw the following error:

```
The option value ``Removed`` is not valid
```
Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Example

```
enum 100510 myEnum
{
ObsoleteState = Removed;
...
}
```
## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0170

Article•11/25/2024

An '=' is expected for property {0}.

An '=' is expected between a property and its value. The correct syntax is Property_name
= value;.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0171

Article•11/25/2024

The property value '{0}' on property '{1}' is not valid.

The specified property value is not valid. For more information, refer to the property's
documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0172

Article•11/25/2024

Operator '{0}' is ambiguous on an operand of type '{1}'.

Unary operator is ambiguous on an operand of such type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0173

Article•11/25/2024

Operator '{0}' cannot be applied to an operand of type '{1}'.

Unary operator cannot be applied to an operand of such type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0174

Article•11/25/2024

Operator '{0}' is ambiguous on operands of type '{1}' and '{2}'.

Binary operator is ambiguous on operands of such types.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0175

Article•11/25/2024

Operator '{0}' cannot be applied to operands of type '{1}' and '{2}'.

Binary operator cannot be applied to operands of such types.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0176

Article•11/25/2024

Expected one of the calculation formula methods
(Average,Count,Exist,Min,Max,Lookup,Sum).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0177

Article•11/25/2024

Invalid application object identifier. A number or an application object name is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0178

Article•11/25/2024

A 'FILTER' keyword or an identifier is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0179

Article•11/25/2024

An identifier or a member access expression is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0180

Article•11/25/2024

A 'FILTER' keyword is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0181

Article•11/25/2024

Invalid filter expression.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0182

Article•11/25/2024

An identifier or a literal is expected as the value of a filter expression.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0183

Article•11/25/2024

Unexpected character '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0184

Article•11/25/2024

The expression '{0}' is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0185

Article•11/25/2024

{0} '{1}' is missing.

The referenced application object does not exist.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0186

Article•11/25/2024

Reference '{0}' in application object '{1}' does not exist.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0187

Article•11/25/2024

Attribute '{0}' is valid only for {1}.

The specified attribute is not allowed on such element. For more information, refer to
the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0189

Article•11/25/2024

Attribute '{0}' cannot be specified, because '{1}' is already specified.

Mutually exclusive attributes have been specified on the same variable or method. This
is the case for handler attributes and event attributes, where only one attribute of each
kind can be set on the same procedure.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0190

Article•11/25/2024

Constant value '{0}' is outside the range for a Time.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0191

Article•11/25/2024

Constant value '{0}' is outside the range for a Date. The syntax for defining Date format
is yyyymmddD, where D is a mandatory letter. For example, 20180325D, read as the
25th of March, 2018.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0192

Article•11/25/2024

The return value must be used for the method '{0}'.

The return value of a method must be used.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0193

Article•11/25/2024

Argument {0}: cannot convert from '{1}' to the type of Argument 1 '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0195

Article•11/25/2024

Invalid permission kind. Expected: '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0196

Article•11/25/2024

The call is ambiguous between the method '{0}' defined in {1} '{2}' by the extension '{3}'
and the method '{4}' defined in {5} '{6}' by the extension '{7}'.

The method call is ambiguous between two methods.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0197

Article•11/25/2024

An application object of type '{0}' with name '{1}' is already declared by the extension
'{2}'.

Multiple application objects with the same name are defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0198

Article•11/25/2024

Expected one of the application object keywords ({0}).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0199

Article•11/25/2024

The type of the sum index field '{0}' must be numeric (Decimal, BigInteger, Integer, or
Duration).

Only fields of the numeric type (Decimal, BigInteger, Integer, or Duration) can be used
as sum index fields.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0201

Article•11/25/2024

The {0} FlowField is not a Boolean field. If a FlowField CalcFormula starts with 'Exist', then
the FlowField must be a Boolean type field.

If a FlowField CalcFormula starts with 'Exist', then the FlowField must be a Boolean type
field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0202

Article•11/25/2024

The {0} FlowField is not an Integer field. If a FlowField CalcFormula starts with 'Count',
then the FlowField must be an Integer type field.

If a FlowField CalcFormula starts with 'Count', then the FlowField must be an Integer
type field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0203

Article•11/25/2024

Cannot calculate Sum or Average for the field {0} because it is not a numeric field
(Decimal, BigInteger, Integer, or Duration data type).

Only fields of the numeric type (Decimal, BigInteger, Integer, or Duration) can be used
to calculate Sum or Average for a field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0204

Article•11/25/2024

Field type {0} is not convertible to field type {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0206

Article•11/25/2024

A field with ID {0} is already defined in {1} '{2}' by the extension '{3}'.

There are multiple fields with the same ID defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0207

Article•11/25/2024

The expression must be of Text type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0208

Article•11/25/2024

The expression must be of Boolean type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0210

Article•11/25/2024

A control with ID = {0} is already defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0211

Article•11/25/2024

Unknown area type '{0}'.

The type of the area defined is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0212

Article•11/25/2024

An area of type '{0}' is already defined.

There are multiple areas of the same type defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0213

Article•11/25/2024

An area of type '{0}' is only valid on pages of type(s) '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0214

Article•11/25/2024

An area of type 'FactBoxes' is not valid on Part type pages.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0215

Article•11/25/2024

A Part type page cannot contain other parts.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0216

Article•11/25/2024

Only parts are valid in an area of type 'FactBoxes'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0217

Article•11/25/2024

Only parts and groups are valid in an area of type 'RoleCenter'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0218

Article•11/25/2024

An integer literal value is expected for property {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0219

Article•11/25/2024

Syntax error, string literal expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0220

Article•11/25/2024

Syntax error, boolean literal expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0221

Article•11/25/2024

The value '{0}' is not valid. The valid range is {1}..{2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0222

Article•11/25/2024

The ID '{0}' is not valid. ID's must be greater than zero.

An object ID must be greater than 0.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0223

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set to '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0224

Article•11/25/2024

Expression expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0227

Article•11/25/2024

A key with ID {0} is already defined.

Multiple keys with the same ID are defined in the same table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0228

Article•11/25/2024

A field group with ID {0} is already defined.

Multiple field groups with the same ID are defined in the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0229

Article•11/25/2024

The data type on the {0} field is not valid because the ExtendedDatatype property is set
to Ratio. Valid data types are Integer, BigInteger and Decimal.

If a field has the **ExtendedDatatype** property is set to **Ratio** , then the field can only be of
the type Integer, BigInteger or Decimal.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0230

Article•11/25/2024

The data type on the {0} field is not valid because the ExtendedDatatype property is set
to PhoneNo, URL or Email. Valid data types are Code and Text.

If a field has the **ExtendedDatatype** property is set to **PhoneNo** , **URL** or **Email** , then the
field can only be of the type Code or Text.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0231

Article•11/25/2024

A member with ID '{0}' is already defined in {1} '{2}' by the extension '{3}'.

Multiple members with the same ID have been defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0232

Article•11/25/2024

The property value on field '{0}' must be positive or zero.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0234

Article•11/25/2024

An action with ID = {0} is already defined.

Multiple actions with the same ID are defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0236

Article•11/25/2024

An empty CONST() expression is not allowed on field '{0}' of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0238

Article•11/25/2024

No overload for attribute '{0}' expects {1} arguments.

The attribute has been specified with the wrong number of attributes. For more
information, see the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0239

Article•11/25/2024

Attribute {0} is specified multiple times.

The same attribute has been specified multiple times on the same element.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0240

Article•11/25/2024

The signature of procedure '{0}' does not match the signature required by attribute '{1}':
parameter {2} is expected to be of type '{3}' but found type '{4}'. The expected signature
is: {5}.

The parameter type of the procedure where the attribute is set does not match the
signature required by attribute. For more information about the required signature, see
the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0241

Article•11/25/2024

The signature of procedure '{0}' does not match the signature required by attribute '{1}'.
The expected signature is: {2}.

The parameter count of the procedure where the attribute is set does not match the
signature required by attribute. For more information about the required signature, see
the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0242

Article•11/25/2024

Invalid attribute argument syntax: '{0}'.

The attribute argument syntax is not valid. For more information, see the attribute's
documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0243

Article•11/25/2024

Attribute {0} can only be used within a codeunit of subtype {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0244

Article•11/25/2024

The signature of procedure '{0}' does not match the signature required by attribute '{1}':
return value is expected to be of type '{2}' but found type '{3}'. The expected signature
is: {4}.

The return value of the procedure where the attribute is set does not match the
signature required by attribute. For more information about the required signature, see
the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0245

Article•11/25/2024

The signature of procedure '{0}' does not match the signature required by attribute '{1}':
procedure cannot be local.

The visibility of the procedure where the attribute is set does not match the signature
required by attribute. For more information about the required signature, see the
attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0246

Article•11/25/2024

The property '{0}' cannot be customized.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0247

Article•11/25/2024

The target {0} '{1}' for the extension object is not found.

The target for an extension object is not found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0250

Article•11/25/2024

The data type on the {0} field is not valid because the ExtendedDatatype property is set
to Person. Valid data types are Media and MediaSet.

If a field has the **ExtendedDatatype** property is set to **Person** , then the field can only be
of the type Media or MediaSet.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0252

Article•11/25/2024

Expected 'Ascending' or 'Descending' value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0255

Article•11/25/2024

Property '{0}' requires an application object reference for the 'RunObject' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0256

Article•11/25/2024

The flowfield '{0}' cannot be part of the keys for table '{1}'.

A FlowField cannot be part of the keys of a table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0257

Article•11/25/2024

Constant value '{0}' is outside the range for a DateTime data type, only 0 is valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0259

Article•11/25/2024

A SQLIndex defined for the primary key must contain the same fields as the key for table
'{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0260

Article•11/25/2024

The key '{0}' on table '{1}' cannot start with the fields defined for the primary key. The
server will append these to any alternate key.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0261

Article•11/25/2024

The identifier '{0}' can only be specified in the list once.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0262

Article•11/25/2024

The clustered key '{0}' has already been defined for table '{1}'.

A clustered key can only be defined once in the same table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0263

Article•11/25/2024

The primary key '{0}' on table '{1}' (the first one in the key list) must be enabled.

The primary key of a table must have the **Enabled** property set to true.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0264

Article•11/25/2024

An application object of type '{0}' with ID '{1}' is already declared by the extension '{2}'.

Multiple application objects of the same type and with the same ID are defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0267

Article•11/25/2024

Actions are not allowed on the control type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0268

Article•11/25/2024

Grouping of actions is not allowed.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0270

Article•11/25/2024

The control '{0}' is not found in the target '{1}'.

Missing referenced control.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0271

Article•11/25/2024

The action '{0}' is not found in the target '{1}'.

Missing referenced action.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0272

Article•11/25/2024

The anchoring symbol '{0}' must be a grouping symbol.

An anchoring symbol must be a grouping symbol.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0274

Article•11/25/2024

The anchoring symbol '{0}' cannot be an area.

An anchoring symbol cannot be an area.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0275

Article•11/25/2024

'{0}' is an ambiguous reference between '{1}' defined by the extension '{2}' and '{3}'
defined by the extension '{4}'.

Ambiguous reference between two symbols.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0276

Article•11/25/2024

A Time literal value is expected for property {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0277

Article•11/25/2024

A Date literal value is expected for property {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0278

Article•11/25/2024

A DateTime literal value is expected for property {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0279

Article•11/25/2024

The key '{0}' on table '{1}' contains too many fields.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0280

Article•11/25/2024

The event '{0}' is not found in the target.

The referenced event is missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0281

Article•11/25/2024

Object member '{0}' is not an event.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0282

Article•11/25/2024

The member referenced by event subscriber '{0}' parameter '{1}' is not found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0283

Article•11/25/2024

The event '{0}' must not have a return value.

An event must not have a return value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0284

Article•11/25/2024

The type of the parameter '{1}' on the event subscriber '{0}' does not match the
expected type '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0285

Article•11/25/2024

The event '{0}' must not have a parameter name 'sender' when it specifies to include
sender.

An event publisher must not have a parameter name 'sender' when it specifies to
include sender.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0286

Article•11/25/2024

The event '{0}' can't contain code.

An event can't contain code.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0287

Article•11/25/2024

The event '{0}' can't contain local variables.

An event can't contain local variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0288

Article•11/25/2024

Parameter '{0}' is only allowed to be 'var' if the publisher parameter is 'var'.

The parameter of an event subscriber is only allowed to be 'var' if the publisher
parameter is 'var'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0290

Article•11/25/2024

Element name is not allowed for the event '{0}' and must be empty.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0291

Article•11/25/2024

Event trigger '{0}' can only be used if the page specifies the 'SourceTable' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0292

Article•11/25/2024

'FIELD', 'CONST' or 'FILTER' keyword is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0293

Article•11/25/2024

Property value {0} is not in the field's OptionMembers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0294

Article•11/25/2024

The type of property value {0} does not match the field’s type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0295

Article•11/25/2024

The field '{0}' is not found in the target '{1}'.

The referenced field is missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0296

Article•11/25/2024

The application object or method '{0}' has scope '{1}' and cannot be used for '{2}'
development.

For more information, see Compilation Scope Overview.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0297

Article•11/25/2024

The application object identifier '{0}' is not valid. It must be within the allowed ranges
'{1}'.

An application object's ID must be within the idRange specified in the manifest.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0298

Article•11/25/2024

The data type of the expression assigned to the 'StyleExpr' property is not valid. Valid
data types are Boolean, Text, or Code.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0300

Article•11/25/2024

The property '{0}' is used as a method.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0301

Article•11/25/2024

A list must end with a member; not a separator {0}.

A list cannot end with a separator.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0302

Article•11/25/2024

Cannot use '{0}' in {1} '{2}' before it is declared.

Cannot use an element before it is declared.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0303

Article•11/25/2024

Attributes can only be defined on variables and methods.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0304

Article•11/25/2024

Length of the identifier '{0}' cannot exceed {1} characters.

The length of an identifier cannot exceed 120 characters.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

# Compiler Error AL0305

Article•11/25/2024

The length of the application object identifier '{0}' cannot exceed {1} characters.

The length of an application object identifier cannot exceed 30 characters.

This diagnostic will be triggered, for example, if you create a permission set with a name
longer than 30 characters, with the Assignable property set to false. For permission

sets specifically, the diagnostic will also be triggered, if a permission set with the
Assignable property set to true exceeds 20 characters.

```
AL
```
```
AL
```
```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Remarks

```
permissionset 50111 NameExceeds30CharactersByFivePlusSome
{
Assignable = false;
Permissions =
table Customer = X;
}
```
```
permissionset 50112 NameExceeds20Characters
{
Assignable = false;
Permissions =
table Customer = X;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0306

Article•11/25/2024

A field list has to contain at least one field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0307

Article•11/25/2024

Property value cannot be validated because the source table is unreachable.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0308

Article•11/25/2024

The primary key '{0}' on table '{1}' (the first one in the key list) must have the
MaintainSqlIndex property set to true.

The primary key of a table must have the **MaintainSqlIndex** property set to true.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0309

Article•11/25/2024

Table '{0}' contains too many keys.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0310

Article•11/25/2024

An instance is required for the non-static member '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0311

Article•11/25/2024

Member '{0}' cannot be accessed with an instance reference; qualify it with '{1}' instead.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0313

Article•11/25/2024

Attribute {0} can only be used within {1}.

The referenced attribute cannot be set within such object. For more information about
where the attribute is allowed in, refer to the attribute's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0314

Article•11/25/2024

The property '{0}' is only valid in controls of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0315

Article•11/25/2024

Control '{0}' does not exist in group '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0316

Article•11/25/2024

The expression must be of Integer type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0317

Article•11/25/2024

A property with the same name has already been declared.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0318

Article•11/25/2024

The value assigned to the 'RunObject' property is not valid. Valid object types are
codeunit, page, xmlport, report, and query.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0319

Article•11/25/2024

At least one target has to be specified for the move.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0320

Article•11/25/2024

The referenced page '{0}' must specify a 'SourceTable'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0321

Article•11/25/2024

Variable {0} cannot be included in the data set.

Only variables of the type BigInteger,Boolean, Char, Decimal, Integer, Option, Enum, Text
and Code can be included in the data set.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0322

Article•11/25/2024

{0} is not valid for client expressions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0323

Article•11/25/2024

The value assigned to the SystemPart type is not valid. Valid values are {0}.

The value assigned to the SystemPart type must be Notes, Links, MyNotes or Outlook.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0324

Article•11/25/2024

The language {0} must only be specified one time.

The same language has been specified multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0325

Article•11/25/2024

The field '{0}' in the table '{1}' cannot be included in a key because its type is '{2}'.

Only fields of the type Guid, Decimal or Integer can be included in a key.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0326

Article•11/29/2024

'{0}' is not a valid column type.

The specified data type is not valid for columns. Valid data types are Boolean, Char,
Integer, BigInteger, Decimal, Option, Enum, Text, Code, TextConst, Label, DateTime, Time,
Date, DateFormula, Duration, Guid, RecordId, TableFilter, String, Blob, Media, Variant and
MediaSet.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Remarks

```
２ Warning
```
```
From Business Central 2021 release wave 1, report columns can no longer be of the
type 'Variant'. For more information, see Compiler Error AL0638.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0327

Article•11/25/2024

Missing file '{0}'.

The referenced file is missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0329

Article•11/25/2024

The {0} property must reference a top-level DataItem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0331

Article•11/25/2024

The property 'DataItemLink' cannot be set on a top-level DataItem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0332

Article•11/25/2024

The control {0} must be of type {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0333

Article•11/25/2024

The syntax for accessing fields is not valid. Specify target field with
'tableName.fieldName' syntax.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0334

Article•11/25/2024

The extension object '{0}' cannot be declared. Another extension for target '{1}' or the
target itself is already declared in this module.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0335

Article•11/25/2024

Attributes must be specified before elements inside of an element.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0336

Article•11/25/2024

There must be exactly one root node and it has to be an element.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0337

Article•11/25/2024

None of the specified parent table elements has the name {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0338

Article•11/25/2024

Event trigger '{0}' can only be used if the page specifies 'SourceTable'. Table '{1}' is
missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0340

Article•11/25/2024

Page '{0}' should be of type 'RoleCenter'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0341

Article•11/25/2024

'{0}' property is missing.

The referenced property is missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0342

Article•11/25/2024

You cannot combine two DataItems at the same level because unions are not supported.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0343

Article•11/25/2024

Queries must define a top-level DataItem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0344

Article•11/25/2024

The property 'DataItemLink' must be set.

The property 'DataItemLink' must be set for nested DataItems.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0345

Article•11/25/2024

The source of a Column or Filter must be a field defined on the table referenced by its
parent DataItem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0346

Article•11/25/2024

The methods '{0}' can only be used on Columns that have a Date or DateTime type.

The **Method** property can only have the property values Day, Month and Year when
used on Columns of the type Date or DateTime.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0347

Article•11/25/2024

The methods '{0}' can only be used on Columns that have a Decimal, BigInteger, Integer,
or Duration type.

The **Method** property can only have the property values Average, Sum, Max and Min
when used on Columns of the type Decimal, BigInteger, Integer, or Duration.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0349

Article•11/25/2024

Column '{0}' does not exist in application object '{1}'.

The referenced column does not exist in the current application object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0350

Article•11/25/2024

The column '{0}' cannot be used multiple times when defining the order of the resulting
dataset.

A column cannot be used multiple times when defining the order of the resulting
dataset. It can only be selected once the order of the resulting dataset of the query is
defined. The selected duplicate columns must be deleted.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0351

Article•11/25/2024

The property 'DataItemLink' can only reference fields on ancestor data items.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0352

Article•11/25/2024

Queries must define at least one Column.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0353

Article•11/25/2024

A Column must have a valid data source or have the 'Method' property set to 'Count'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0354

Article•11/25/2024

Cannot move element '{0}' relative to itself in page '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0355

Article•11/25/2024

Cannot move the {0} '{1}' multiple times inside of a single move operation.

An element cannot be moved multiple times inside of a single move operation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0356

Article•11/25/2024

Cannot modify the {0} '{1}' multiple times.

The element cannot be modified multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0357

Article•11/25/2024

Cannot add {0} '{1}' with the same name multiple times.

An element with the same name cannot be added multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0358

Article•11/25/2024

Cannot move or modify the {0} '{1}' in the same '{2}' that you added.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0359

Article•11/25/2024

The XML node name is not valid. {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0360

Article•11/25/2024

Text literal was not properly terminated. Use the character ' to terminate the literal.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0361

Article•11/25/2024

Identifier was not properly terminated. Use the character " to terminate the identifier.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0362

Article•11/25/2024

The path must be relative to the project root.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0363

Article•11/25/2024

The directory separator used in this property value is not compatible with the current
operating system.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0364

Article•11/25/2024

Option members must be accessed with ::.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0365

Article•11/25/2024

The property '{0}' cannot be set if the property '{1}' is set to '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0366

Article•11/25/2024

A table has to have at least one Normal field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0367

Article•11/25/2024

An array must have at least one dimension.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0368

Article•11/25/2024

The maximum number of array dimensions is {0}.

The number of dimensions for an array cannot exceed 10.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0369

Article•11/25/2024

Constant value '{0}' cannot be converted to a '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0370

Article•11/25/2024

Division by constant zero.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0371

Article•11/25/2024

The operation overflows at compile time.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0372

Article•11/25/2024

The length of the String constant exceeds the current memory limit.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0373

Article•11/25/2024

The XML name cannot be empty.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0375

Article•11/25/2024

Option members cannot contain comma.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0376

Article•11/25/2024

A control of type '{0}' is not allowed in a parent control of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0377

Article•11/25/2024

'{0}' is not a valid value for the '{1}' attribute on variables of type '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0378

Article•11/25/2024

A page of type Role Center cannot have triggers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0379

Article•11/25/2024

The name '{0}' cannot be used as an identifier because it does not comply with the
Common Language Specification.

For more information about Common Language Specification, see:

What is the Common Language Specification
Unicode Normalization Forms

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0380

Article•11/25/2024

Cannot move symbol '{0}' from '{1}' area to '{2}' area.

Cannot move a symbol between areas.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0381

Article•11/25/2024

The keys '{0}' and '{1}' have an identical list of fields.

Multiple keys have specified the same list of fields.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0382

Article•11/25/2024

The option value '{0}' is defined more than once on field '{1}'.

The same option value has been defined multiple times on the same field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0383

Article•11/25/2024

The option value '{0}' is not defined on field '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0384

Article•11/25/2024

The name of all the columns and all the labels defined in a report must be unique.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0385

Article•11/25/2024

IncludeCaption can be set to true only if the source of the column is a named field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0386

Article•11/25/2024

A required package dependency could not be found. Make sure that you have
downloaded all the referenced packages and their dependencies.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0387

Article•11/25/2024

Namespace '{0}' is already specified.

A namespace has been defined multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0388

Article•11/25/2024

The date formula '{0}' must include plus (+) or minus (-).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0389

Article•11/25/2024

The date formula '{0}' contains a number that is too large. The number must be in the
range {1} - {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0390

Article•11/25/2024

The date formula '{0}' must include a time unit. Time units can be: D,WD,W,M,Q, or Y. C
specifies the current time unit based on date and can be used as a prefix to any of the
time units.

A date formula must include a time unit.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0391

Article•11/25/2024

The date formula '{0}' must include a number.

A date formula must include a number.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0392

Article•11/25/2024

The input cannot be longer than {0}.

A date formula value cannot exceed 32 characters.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0393

Article•11/25/2024

Application object {0} is already referenced.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0395

Article•11/25/2024

You can only specify Move and Modify actions in the layout section of a page
customization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0396

Article•11/25/2024

Procedures and triggers are not allowed on page customizations.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0397

Article•11/25/2024

The name '{0}' clashes with '{1}' column's format column name.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0398

Article•11/25/2024

Constant value '{0}' is outside of the valid ordinal range for this {1} type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0399

Article•11/25/2024

Global variables are not allowed on page customizations.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0401

Article•11/25/2024

Multiple page customizations have been specified for the same page {0} within the same
profile.

Only one page customization per page is allowed within a profile.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0402

Article•11/25/2024

Expression {0} cannot be specified more than once in a 'case' statement.

Duplicate expression in a 'case' statement. Expressions in a 'case' statement must be
unique.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0403

Article•11/25/2024

To modify '{0}' you must add at least one property or trigger.

To modify a field, you must add at least one property or trigger inside the modify
control.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0404

Article•11/25/2024

Property '{0}' is not allowed on a table extension.

The properties **AutoIncrement** , **SqlTimestamp** and **Clustered** , **Unique** are not allowed
on a table extension.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0405

Article•11/25/2024

An option value is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0406

Article•11/25/2024

The type for {0} is not valid. Expected {1}, but found {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0407

Article•11/25/2024

The generic '{0}' type expects {1} type arguments.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0408

Article•11/25/2024

The type '{0}' cannot be used as a type argument in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0409

Article•11/25/2024

The '{0}' type is not a generic type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0410

Article•11/25/2024

The report '{0}' doesn't contain a Request Page.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0411

Article•11/25/2024

{0} can be specified only once.

A label property cannot be specified more than once.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0412

Article•11/25/2024

Member '{0}' could not be declared in an object of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0413

Article•11/25/2024

Procedure '{0}' cannot have a body.

Procedures within **ControlAddin** or **Interface** objects cannot have a body.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0414

Article•11/25/2024

Procedure '{0}' must declare a body.

Procedures must declare a body, except for those defined inside a **ControlAddin** or
**Interface**.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0415

Article•11/25/2024

Keyword 'local' cannot be specified for procedure '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0416

Article•11/25/2024

Method '{0}' cannot have a return value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0417

Article•11/25/2024

Control add-in '{0}' not found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0418

Article•11/25/2024

The format of resource '{0}' is not valid. Resources in the control add-in should either be
relative to the project root, or reference external files using the HTTP or HTTPS protocol.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0419

Article•11/25/2024

The event subscriber '{0}' is missing a parameter of type '{1}'.

The event subscriber is missing a parameter

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0420

Article•11/25/2024

Parameter '{0}' cannot be 'var'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0421

Article•11/25/2024

A ‘foreach’ statement can only be used with an expression of an enumerable type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0422

Article•11/25/2024

Constant value {0} is not a valid value for APIVersion. Valid values are 'beta' or of type
'vX.Y' where X and Y represent positive integers.

The APIVersion property must have the values 'beta' or of type 'vX.Y', where X and Y
represent positive integers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0423

Article•11/25/2024

The property '{0}' can only be set if the specified fields are from the same table.

A property can only be used on keys with fields from the same table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0425

Article•11/25/2024

The '{0}' trigger can only be used on codeunits that have the Subtype property set to
'{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0426

Article•11/25/2024

The APIVersion {0} is specified multiple times.

The APIVersion property has been specified multiple times on the same object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0427

Article•11/25/2024

Field {0} cannot be converted to type {1}.

The type of the result of a calculation formula must match the type of the FlowField
associated with that CalcFormula.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0428

Article•11/25/2024

Cannot specify {0} and {1} property at the same time. Use only the {1} property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0429

Article•11/25/2024

A repeater control can only be added to pages that have a source table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0430

Article•11/25/2024

The parameter '{0}' has a type which is not serializable and therefore cannot be used in
the given context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0433

Article•11/25/2024

{0} '{1}' is removed. {2}.

The referenced object is obsolete.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0434

Article•11/25/2024

Syntax error, numeric literal expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0435

Article•11/25/2024

Syntax error, literal expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0436

Article•11/25/2024

The value of the property '{0}' cannot be empty.

The value of a property cannot be left empty, it must be specified.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0437

Article•11/25/2024

The value of the '{0}' property cannot include empty members.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0438

Article•11/25/2024

The type of value {0} does not match the field’s type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0439

Article•11/25/2024

The label's property is not valid. Possible properties are: {0}.

Invalid parameter for the label data type. For more information about the valid
parameters, see Label Data Type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0440

Article•11/25/2024

The {0} '{1}' already defines a method called '{2}' with the same parameter types in '{3}'.

A method is defined multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0441

Article•11/25/2024

Parameter {0} is only available when the page specifies a 'SourceTable'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0442

Article•11/25/2024

Parameter {0} is only available when the page specifies a 'SourceTable'. Table '{1}' is
missing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0443

Article•11/25/2024

The system object provided is not one of the valid system objects.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0444

Article•11/25/2024

Malformed {0} report layout at location '{1}'. The issue is: '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0445

Article•11/25/2024

The file '{0}' is opened in another application. Close the application to be able to
compile.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0447

Article•11/25/2024

The value '{0}' for the property '{1}' cannot be used for '{2}' development.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0448

Article•11/25/2024

Member is not allowed in this context.

Procedures or variables are not allowed in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0449

Article•11/25/2024

The alias '{0}' is already declared.

There are multiple DotNet types defined with the same alias.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0450

Article•11/25/2024

Field '{0}' is removed and cannot be used in an active key.

An obsolete field cannot be used in a key.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0451

Article•11/25/2024

An assembly named '{0}' could not be found in the assembly probing paths '{1}'.

The referenced assembly could not be found in the assembly probing paths. You must
add the path of the folder containing the assembly to the Al: Assembly Probing Paths
setting on the User Settings or Workspace Settings so the compiler can access it.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0452

Article•11/25/2024

The type '{0}' could not be found in assembly '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0453

Article•11/25/2024

This feature is under development. It can be enabled by using the '{0}' feature flag.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0454

Article•11/25/2024

The {0} {1} of type {2} cannot be extended.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0455

Article•11/25/2024

Option ordinal value '{0}' is not valid. Valid values are -1 and positive integers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0456

Article•11/25/2024

The number of option ordinal values is not valid. There must be as many option ordinal
values as there are option members.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0458

Article•11/25/2024

'{0}' is not a valid attribute on variables of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0459

Article•11/25/2024

The attribute '{0}' is only allowed on global variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0460

Article•11/25/2024

Client-side events are supported only on pages and page extensions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0461

Article•11/25/2024

'{0}' is not a valid event publisher.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0462

Article•11/25/2024

The publisher '{0}' does not have any public events named '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0463

Article•11/25/2024

Parameter '{0}' must be 'var' if and only if the publisher parameter is 'var'.

The parameter of an event subscriber can only if the publisher parameter is 'var.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0464

Article•11/25/2024

Could not determine a suitable default primary key for table '{0}'. Please specify a
primary key for the table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0465

Article•11/25/2024

The property '{0}' does not accept references to external files.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0466

Article•11/25/2024

Cannot access file '{0}'. The file is most likely read-only.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0470

Article•11/25/2024

The referenced page '{0}' of PageType 'HeadlinePart' is only allowed inside pages of
PageType 'RoleCenter'.

Pages of the type 'HeadlinePart' are only allowed inside pages of PageType 'RoleCenter'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0471

Article•11/25/2024

The format of link '{0}' is not valid. It should be using the HTTP or HTTPS protocol.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0474

Article•11/25/2024

The attribute '{0}' is only allowed on local variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0475

Article•11/25/2024

The attribute '{0}' cannot be used on variables of array type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0476

Article•11/25/2024

The trigger '{0}' can only be used if the property '{1}' of '{2}' is set.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0477

Article•11/25/2024

The trigger '{0}' can only be used if the property '{1}' of '{2}' is set to '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0478

Article•11/25/2024

The trigger '{0}' can only be used if the property '{1}' of '{2}' is set with any of the values
of :'{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0480

Article•11/25/2024

Attributes cannot have nested elements.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0484

Article•11/25/2024

The property '{0}' must be alphanumeric.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0485

Article•11/25/2024

The property '{0}' is mandatory for objects of type API.

The properties **EntitySetName** , **EntityName** , **APIPublisher** , **APIGroup** must be set in
page or query objects of the type API.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0487

Article•11/25/2024

The field '{0}' is not of field class 'Normal' and thus cannot be part of the {1} list.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0488

Article•11/25/2024

ControlAddIn name must not contain characters {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0489

Article•11/25/2024

The property expression is not valid. A CONST or FILTER expression is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0490

Article•11/25/2024

The property expression is not valid. A CONST, FIELD, or FILTER expression is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0491

Article•11/25/2024

The property expression is not valid. One of the following expressions is expected :
CONST,FIELD,FILTER,FIELD(FILTER(Identifier)),FIELD(UPPERLIMIT(Identifier)),or
FIELD(UPPERLIMIT(FILTER(Identifier))).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0492

Article•11/25/2024

The RunObject property value of actions defined in the '{0}' area must only reference
pages of type 'List'.

The **RunObject** property value must only reference pages of type 'List'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0494

Article•11/25/2024

The action area '{0}' can only directly contain groups.

An action area con only diretly contain groups.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0495

Article•11/25/2024

A member with ID '{0}' is already defined. Change the member name to generate a new
ID.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0496

Article•11/25/2024

Attributes cannot be defined in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0498

Article•11/25/2024

The attribute '{0}' can only be used on procedures that have the attribute '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0499

Article•11/25/2024

The handler function {0} was not found. Make sure the procedure is defined and has a
handler attribute.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0500

Article•11/25/2024

The HandlerFunctions attribute only accepts a string representing a comma separated
list of procedure names without spaces.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0501

Article•11/25/2024

Eventsubscribers in test codeunits must use manual binding. Set the property
EventSubscriberInstance to Manual.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0502

Article•11/25/2024

The LinkTable property must reference a table element node of the current XMLPort.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0503

Article•11/25/2024

Reference '{0}' in application object '{1}' is ambiguous.

Ambiguous reference to an application object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0504

Article•11/25/2024

The enum '{0}' is not extensible.

The referenced enum is not extensible. Enums are not extensible by default, you must
set the **Extensible** property to * _true_.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0505

Article•11/25/2024

Pages of type API must have the 'DelayedInsert' property set to true. From runtime 7.2,
'DelayedInsert' can be set to false if the 'Editable' property or the 'InsertAllowed'
property is set to false.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0510

Article•11/25/2024

The .NET type '{0}' is not a valid control add-in.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0511

Article•11/25/2024

The property 'IsControlAddIn' must be set on the .NET type '{0}' if the type represents a
.NET control add-in.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0512

Article•11/25/2024

The manifest should define the 'supportedLocales' manifest property in order to use a
placeholder in the '{0}' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0513

Article•11/25/2024

The FieldGroup '{0}' is not found in the target '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0514

Article•11/25/2024

The symbol file is not valid. An enum with ID '{0}' is already defined with a different
name in module '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0515

Article•11/25/2024

The symbol file is not valid. An enum with name '{0}' is already defined with a different
ID in module '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0516

Article•11/25/2024

The symbol file is not valid. An enum with ID '{0}' and name '{1}' is already defined in
module '{2}', but with different values (OptionString).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0517

Article•11/25/2024

The link '{0}' specified in the HelpLink property must either contain one placeholder with
value 0 for the user locale, or no placeholders.

The link specified in the **HelpLink** property must either contain one placeholder with
value 0 for the user locale, or no placeholders.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0518

Article•11/25/2024

A method with name '{0}' possessing one Handler attribute is already defined in this test
codeunit.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0519

Article•11/25/2024

'{0}' is not valid value in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0521

Article•11/25/2024

The primary key '{0}' on table '{1}' (the first one in the key list) must not have the Unique
property set.

The primary key of a table must not have the **Unique** property set to true.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0522

Article•11/25/2024

Property value {0} is not in the values for enum '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0525

Article•11/25/2024

The system or virtual table '{0}' cannot be extended.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0526

Article•11/25/2024

The referenced page '{0}' of type 'API' is only allowed inside pages of PageType 'API'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0527

Article•11/25/2024

The SQL timestamp field '{0}' cannot be part of the keys for table '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0528

Article•11/25/2024

The name of field controls in pages of the type API must be alphanumeric.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0529

Article•11/25/2024

The name of columns in queries of the type API must be alphanumeric.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0530

Article•11/25/2024

The maximum length for the type '{0}' is {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0531

Article•11/25/2024

The page '{1}' of type 'API' and its subpage '{2}' of type 'API' in the control '{0}' of type
'Part' must have the same value of property '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0532

Article•11/25/2024

The page '{1}' of type 'API' and its control '{0}' of type 'Part' must have the same value of
property '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0533

Article•11/25/2024

The view '{0}' is not found in the target '{1}'.

The referenced view is missing in the target page.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0535

Article•11/25/2024

The referenced page '{0}' must be a List part, a Card part, or an API page.

A page used for a part control of an API page must be a List part, a Card part, or an API
page.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0536

Article•11/25/2024

Adding new controls in a view is not allowed.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0537

Article•11/25/2024

Declaring views is only supported on pages of type {0}.

Declaring views is only supported on pages, page extensions, and page customization of
the type List.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0538

Article•11/25/2024

Views only support setting one sorting direction on table fields.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0539

Article•11/25/2024

The field '{0}' cannot be used multiple times when defining the order of the page view.

The same field cannot be reference multiple times when defining the order of the page
view.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0540

Article•11/25/2024

The view name '{0}' is not valid.

The name of a view cannot be empty or a whitespace.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0541

Article•11/25/2024

The use of the variable '{0}' in the property value of '{1}' in view '{2}' is not allowed.

It is not allowed to use boolean expressions as the proeprty value of properties defined
in a view.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0542

Article•11/25/2024

The property {0} cannot be used on page '{1}' because this page does not have a source
table.

The properties **OrderBy** and **Filters** cannot be used on pages without a source table.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0543

Article•11/25/2024

The manifest property 'contextSensitiveHelpUrl' must be set in order to use the property
'ContextSensitiveHelpPage'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0544

Article•11/25/2024

The property 'ContextSensitiveHelpPage' cannot contain a placeholder.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0546

Article•11/25/2024

The control '{0}' cannot be modified in a view context because views only support
modifying controls defined in the Content area.

Views only support modifying controls defined in the Content area.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0549

Article•11/25/2024

Procedures and triggers are not allowed on page views.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0553

Article•11/25/2024

You cannot add actions of type '{0}' in the action area '{1}' from a page customization.
You can only add actions of type '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0554

Article•11/25/2024

You can only specify Move and Modify actions in the actions section of a page
customization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0555

Article•11/25/2024

The RunObject property value of actions defined in the '{0}' area must only reference
objects of type {1}.

The **RunObject** property value must only reference objects of type 'Codeunit', 'Page',
'Report', or 'XmlPort'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0564

Article•11/25/2024

The object {0} '{1}' is not extensible.

API pages or objects with the **Extensible** property set to **false** cannot be extended.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0565

Article•11/25/2024

Fast publishing requires a built application file to be present. The '{0}' application file
contains a manifest which is not valid. Please rebuild the application file before
continuing with fast publishing.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0566

Article•11/25/2024

The field '{0}' is using an Id {1} that is reserved for system fields.

A field is using an ID bigger or equal to 2000000000, which is a value reserved for
system fields.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0570

Article•11/25/2024

The symbol '{0}' results in the same translation ID as one or more other symbols.
Rename symbol to resolve the problem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0572

Article•11/25/2024

I/O operations on the file or folder '{0}' resulted in an exception with the Windows 32
error code '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0574

Article•11/25/2024

This feature is under development and cannot be used in an extension.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0575

Article•11/25/2024

You cannot reference the {0} '{1}' because it is defined in the page customization '{2}'.

You cannot reference an element defined in a page customization outside the page
customization declaring it.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0576

Article•11/25/2024

The profile name '{0}' is not valid because it contains leading or trailing spaces.

The name for a progile must not contain leading or trailing spaces.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0577

Article•11/25/2024

The view '{0}' cannot define layout changes because its property '{1}' is not set to false.

A view should have the **SharedLayout** property set to false in order to have layout
changes.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0578

Article•11/25/2024

The value for the property '{0}' is not valid because its length exceeds {1} characters ({2}
characters).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0579

Article•11/25/2024

The value for the property '{0}' for the language code '{1}' is not valid because its length
exceeds {2} characters ({3} characters).

The length of the value for any language code in a multilanguage property defined in a
profile or profile extension should not exceed 100 characters.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0580

Article•11/25/2024

The field '{0}' is used by the system and cannot be specified as a table key.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0581

Article•11/25/2024

The length for the type '{0}' must be positive.

The length specified for a data type must be possitve.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0582

Article•11/25/2024

'{0}' does not implement the interface member '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0584

Article•11/25/2024

An interface member cannot have any variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0585

Article•11/25/2024

An interface cannot have any variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0587

Article•11/25/2024

'{0}' is already listed in the interface list.

Multiple interfaces have been listed within the same interface implementation list.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0591

Article•11/25/2024

The property {0} is only supported on {1}.

The referenced property is not supported on the element is was set on. For more
information on the elements the property applies to, refer to the property's
documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0594

Article•11/25/2024

An error occurred during XML serialization of metadata for symbol: '{0}'. Error: {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0595

Article•11/25/2024

'{0}' does not implement {1}.

The referenced application object does not implement the specified interface.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0596

Article•11/25/2024

Value '{0}' does not implement interface '{1}' and there is no default implementation for
the mentioned interface.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0599

Article•11/25/2024

A control add-in with the same internal name '{0}' is already defined.

Multiple control add-ins with the same metadata name are defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0612

Article•11/25/2024

An interface member must be a 'procedure'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0616

Article•11/25/2024

Defining the contract '{0}' on interface '{1}' is not allowed because it is matching a built-
in procedure for codeunits.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0619

Article•11/25/2024

The attribute '{0}' on procedure '{1}' is not allowed. Add attribute 'ServiceEnabled' to the
procedure or move it into an application object of type API.

The Caption attribute is not allowed. Add attribute 'ServiceEnabled' to the procedure or
move it into an application object of type API.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0620

Article•11/25/2024

Preprocessor directives must appear as the first non-whitespace character on a line.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0621

Article•11/25/2024

Preprocessor directive expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0622

Article•11/25/2024

#endregion directive expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0623

Article•11/25/2024

#endif directive expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0624

Article•11/25/2024

Unexpected preprocessor directive.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0625

Article•11/25/2024

Cannot define/undefine preprocessor symbols after first token in file.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0629

Article•11/25/2024

Preprocessor expression is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0630

Article•11/25/2024

Unrecognized escape sequence.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0631

Article•11/25/2024

Single-line comment or end-of-line expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0632

Article•11/25/2024

Closing parenthesis ')' expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0636

Article•11/25/2024

The data type on the field '{0}' is not valid because the ExtendedDatatype property is set
to RichText. Valid data types are Text, BigText and Blob.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0637

Article•11/25/2024

The property 'NavigationPageId' must be defined on a page of pagetype 'API'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0638

Article•11/25/2024

'Variant' is not a valid column type for column '{0}' in report '{1}'.

A report column must not be of the type 'Variant'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0648

Article•11/25/2024

End-of-file found, '*/' expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0651

Article•11/25/2024

'{0}' cannot be contained since it causes a circular reference.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0652

Article•11/25/2024

The permission set '{0}' cannot contain itself.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0653

Article•11/25/2024

Ids are not supported as object reference.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0654

Article•11/25/2024

The property value contains an unexpected file extension: {0}. The expected extensions
are {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0656

Article•11/25/2024

The {0} '{1}' cannot be used as an anchor because it is already defined in the same '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0657

Article•11/25/2024

The property {0} is mandatory for ListParts and PageParts.

The properties **EntitySetName** and **EntityName** are mandatory for ListParts and
PageParts nested in API pages.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0658

Article•11/25/2024

Member name '{0}' is only allowed on triggers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0665

Article•11/25/2024

'{0}' is not a valid return type in runtime version '{1}'. The supported runtime versions
are: {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0666

Article•11/25/2024

'{0}' is not available in runtime version '{1}'. The supported runtime versions are: {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0668

Article•11/25/2024

This feature is not available on cross-platform builds of the AL compiler.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0670

Article•11/25/2024

Fast publishing failed because the RAD file has specified a non-existing application
object of type : '{0}' name: '{1}' ID: '{2}' to be added or modified. Please do a full
publishing before issuing a fast publishing again.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0671

Article•11/25/2024

Fast publishing failed because the RAD file has specified an existing application object of
type: '{0}' name: '{1}' ID: '{2}' to be deleted. Please do a full publishing before issuing a
fast publishing again.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0672

Article•11/25/2024

Filtering is only allowed on fields where FieldClass is set to Normal. Create a Filter
column and specify the filter by using the 'ColumnFilter' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0673

Article•11/25/2024

The property '{0}' is required.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0674

Article•11/25/2024

The property '{0}' is required when property '{1}' is set to '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0675

Article•11/25/2024

An implementation for the interface '{0}' is already specified in this list.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0676

Article•11/25/2024

The member '{0}' in object '{1}' cannot be declared as protected in object type '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0680

Article•11/25/2024

Cannot use addBefore or addAfter on a top-level data item. The anchor {0} is a top level
data item.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0681

Article•11/25/2024

A DataItem with name '{0}' could not be found in the target {1}.

The referenced DataItem could not be found in the target report.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0682

Article•11/25/2024

A DataItem or Column with name '{0}' could not be found in the target {1}.

The reference DataItem or Column could not be found in the target report.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0683

Article•11/25/2024

The permissionset '{0}' belongs to a different module and cannot be used when defining
entitlements.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0686

Article•11/25/2024

The base type already defines a method called '{0}' with the same parameter types.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0687

Article•11/25/2024

The key '{0}' on table '{1}' cannot contain the fields defined for the primary key in the
IncludeFields property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0688

Article•11/25/2024

The key '{0}' on table '{1}' cannot contain the fields defined for the key in the
IncludeFields property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0689

Article•11/25/2024

The key '{0}' on table '{1}' cannot contain the fields defined for the SqlIndex in the
IncludeFields property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0690

Article•11/25/2024

The primary key '{0}' on table '{1}' (the first one in the key list) must not have the
IncludedFields property set.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0691

Article•11/25/2024

The primary key '{0}' on table '{1}' cannot be obsolete. All related properties will have no
effect.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0693

Article•11/25/2024

The field '{0}' which is part of the primary key of table '{1}' cannot be obsolete. All
related properties will have no effect.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0696

Article•11/25/2024

Argument {0}: The argument should be a valid Field type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0698

Article•11/25/2024

Type {0} cannot be used in a 'case' statement.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0699

Article•11/25/2024

The symbol '{0}' cannot be referenced in this context. You can only reference symbols
from the base object '{1}', from extension objects defined in this app with an ID lower or
equal to '{2}', or from extension objects defined in dependencies.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0701

Article•11/25/2024

Dependency '{0}' must be referenced in the property '{1}' rather than as an explicit
dependency.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0703

Article•11/25/2024

Dependency '{0}' is referenced in the property '{1}' and as an explicit dependency.
Remove the explicit dependency.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0704

Article•11/25/2024

A layout must be specified through the 'ExcelLayout' property when the default layout
type for a report is 'Excel'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0705

Article•11/25/2024

Another layout with name '{0}' already exists.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0706

Article•11/25/2024

The property '{0}' cannot be used while also specifying the rendering section.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0707

Article•11/25/2024

Layouts of type '{0}' must specify a LayoutFile with one of the following extensions: {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0708

Article•11/25/2024

MimeType values must be less than {0} characters in length.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0709

Article•11/25/2024

The layout file at path '{0}' specified in layout '{1}' in {2} {3} does not exist.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0710

Article•11/25/2024

The DefaultRenderingLayout property can only be used with layouts specified in the
report's rendering section.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0712

Article•11/25/2024

A member of type {0} with name '{1}' is already defined in {2} '{3}' by the extension '{4}'.
Duplicate member names are not allowed when defining CueActions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0713

Article•11/25/2024

Events in control add-ins should be implemented as triggers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0714

Article•11/25/2024

The name '{0}' is an Area type. Using an Area type name will limit extensibility as
dependent extension won't be able to reference it.

Reusing the Area type as the name of a control, action, or variable might lead to
extensibility limitations.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0716

Article•11/25/2024

The {0} name '{1}' is reserved for future AL language features.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0718

Article•11/25/2024

Report layouts must have a name.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0720

Article•11/25/2024

An application object '{0} {1}' could not be found in the current extension. Only
application objects that belong to the current extensions can be used in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0721

Article•11/25/2024

Reports that use the rendering syntax must also define the DefaultRenderingLayout
property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0722

Article•11/25/2024

The property '{0}' is not allowed on {1} '{2}' because the {3} '{4}' is using the ActionRef
syntax or the app.json specifies the 'NoPromotedActionProperties' feature.

0 - the property; 1 - the containing element type; 2 - the containing element name; 3 -
the containing object type; 4 - the containing object name

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0723

Article•11/25/2024

The {0} '{1}' cannot be used as target of the ActionRef '{2}'. ActionRefs can only target
Actions.

0 - the action type (action, separator, area, group); 1 - the name of the target action; 2 -
the name of the action ref

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0724

Article•11/25/2024

An area of type '{0}' is not valid on pages of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0725

Article•11/25/2024

The action type '{0}' is not allowed in area '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0726

Article•11/25/2024

An identifier, a literal, or an option access is expected as the value of a filter expression.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0730

Article•11/25/2024

The field '{0}' cannot be used in a sum index.

The SystemRowVersion field cannot be used as a sum index field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0732

Article•11/25/2024

Access modifier '{0}' is not allowed for member '{1}' in the context of object type '{2}'.

The access modifier is not allowed for the declared member in the context of the
containing type.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0734

Article•11/25/2024

The value '{0}' of the property '{1}' is not a valid GUID.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0735

Article•11/25/2024

The custom action '{0}' cannot be defined in {1} '{2}' because '{2}' uses promoted action
properties. Convert the promoted properties into ActionRefs in oder to use custom
actions.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0736

Article•11/25/2024

The value '{0}' of the property 'FlowEnvironmentId' is not a valid. It must either be a
GUID or must match the pattern 'Default-'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0737

Article•11/25/2024

The {0} '{1}' cannot be referenced in {2} '{3}' because '{1}' is defined in the promoted part
of the action part while '{3}' uses promoted action properties.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0738

Article•11/25/2024

The name of {0} '{1}' cannot be empty.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0740

Article•11/25/2024

The permission set '{0}' cannot be excluded and included in the same permission set.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0741

Article•11/25/2024

The permission set '{0}' cannot exclude itself.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0742

Article•11/25/2024

The property '{0}' is not valid for action '{1}' defined in control '{2}' of type '{3}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0744

Article•11/25/2024

The property '{0}' is not valid for action '{1}' defined in a report request page.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0746

Article•11/25/2024

The auto-increment field '{0}' has already been defined for table '{1}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0747

Article•11/25/2024

The data type on the '{0}' control is not valid for this ExtendedDataType value. Valid data
types are BigText and Text without max size.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0750

Article•11/25/2024

Enum values can't be nested. Use '{0}' instead.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0752

Article•11/25/2024

The name of a dataitem cannot be empty because it can cause runtime errors.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0754

Article•11/25/2024

The '{0}' already defines a built-in member called '{1}'. Choose another name for {2} '{1}',
or it might cause runtime issues.

A built-in member with the same name is already defined for the object, which can
cause runtime errors.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0757

Article•11/25/2024

The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the extension '{5}'.
Choose another name for one of them. Otherwise, this might cause runtime issues.

White spaces in names are internally replaced with an underscore during compilation, so
that two different names can collide.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0759

Article•11/25/2024

The value '{0}' specified for FormatRegion cannot be parsed as a valid format culture
name.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0760

Article•11/25/2024

The value '{0}' specified for FormatRegion is not a standard format culture name.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0761

Article•11/25/2024

An incorrect value was used for the category. One of the values of the enum {0} {1} is
expected which is available in platform version {2} and higher.

The enum provided for the category is wrong.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0762

Article•11/25/2024

Length of the argument '{0}' cannot exceed {1} characters.

The length of the given argument exceeds the maximum length permitted for its type.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0763

Article•11/25/2024

{0} can contain only underscores and alphanumeric characters.

The mentioned argument must be alphanumeric.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0764

Article•11/25/2024

{0} cannot be empty.

The mentioned argument cannot be empty.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0765

Article•11/25/2024

An argument of type {0} cannot be used in an External Business Event.

An invalid argument type is used in the payload of an External Business Event.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0766

Article•11/25/2024

An External Business Event with {0} {1} and version {2} is already declared.

A duplication in the name or display name and the same version of an external business
event is detected.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0767

Article•11/25/2024

The URL '{0}' cannot be used as the ruleset path for this project because its
configuration does not permit external rulesets.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0772

Article•11/25/2024

The attribute '{0}' can only be used in combination with attribute '{1}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0774

Article•11/25/2024

Try methods should not specify an explicit return value, because the value will be
discarded. The actual return value depends on whether the method returns an error or
not.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0776

Article•11/25/2024

The identifier '{0}' is not a valid permission value.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0777

Article•11/25/2024

The implicit conversion will overflow when converting from a 'Guid' to a '{0}' which is
shorter than the converted textual representation of a 'Guid'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0779

Article•11/25/2024

It is not allowed to assign a value to a field of FieldClass='{0}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0781

Article•11/25/2024

Cannot find a reference of DataItem with name '{0}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0783

Article•11/25/2024

A page extension is only allowed to access control add-ins defined within its own
extension scope.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0784

Article•11/25/2024

The version number '{0}' for the argument '{1}' does not match the expected format: X.Y
where X and Y represent positive integers.

The provided version is malformed.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0785

Article•11/25/2024

The control with name '{0}' cannot be declared in the page customization '{1}' targeting
page '{2}' because controls of type '{3}' are not supported in page customizations.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0786

Article•11/25/2024

The property '{0}' cannot be specified on the control '{1}' in the page customization '{2}'
targeting page '{3}', because this property type is not supported in page customizations.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0787

Article•11/25/2024

The control with name '{0}' cannot be declared in the page customization '{1}' targeting
page '{2}' because it is not using a source table field as source expression.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0791

Article•11/25/2024

The namespace '{0}' is unknown.

The namespace is not declared in the scope of the current compilation.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0793

Article•11/25/2024

The property '{0}' cannot be used on a multi-select action with '{1}' scope.

Actions which operate on multiple rows at a time cannot have properties which would
direct the action to navigate elsewhere in the product.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0794

Article•11/25/2024

The value '{0}' for property '{1}' is not valid for action '{2}' defined in control '{3}' of type
'{4}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0795

Article•11/25/2024

The parameter '{0}' cannot be of type 'SecretText'.

Parameters of type 'SecretText' are not allowed on events to prevent unintended leakage
of confidential values.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0797

Article•11/25/2024

{0} '{1}' is moved. {2}.

The referenced object is moved to another extension.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0798

Article•11/25/2024

Currently, the Moved(To/From) property is exclusively accessible to Microsoft and select
publishers.

Only First Party Apps can move symbols.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0799

Article•11/25/2024

The field with ID '{0}' and name '{1}' cannot be used as source expression in the page
customization '{2}' targeting page '{3}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0800

Article•11/25/2024

The field '{0}' specifies ExtendedDataType '{1}'. This ExtendedDataType can only be set
on a control.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0802

Article•11/25/2024

The parameter '{0}' cannot be of type 'SecretText'.

Parameters of type 'SecretText' are not allowed on control add-in procedures to prevent
leakage of confidential values to the browser.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0806

Article•11/25/2024

The object ID '{0}' should not be surrounded with quotes.

Quoted identifiers should not be used to specify object IDs. Integer literals should be
used instead.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0808

Article•11/25/2024

You cannot set the '{0}' property to '{1}' for {2} '{3}' in the page customization '{4}'.

You cannot reference an element defined in a page customization outside the page
customization declaring it.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0809

Article•11/25/2024

The variable '{0}' is not allowed to be of type 'SecretText' because it is declared as
protected.

Protected variables cannot be of type 'SecretText' as that could lead to the accidental
exposure of the secret value to an extension.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0810

Article•11/25/2024

The name '{0}' cannot be used for a system action. The allowed names in a '{1}' page are:
'{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0811

Article•11/25/2024

The trigger '{0}' cannot be defined on the system action named '{1}' in a page of type
'{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0812

Article•11/25/2024

The control '{0}' cannot be declared in the 'PromptOptions' area because it is not a page
field of type 'Option'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0813

Article•11/25/2024

The property '{0}' can only be specified when the property '{1}' has a value of '{2}' if the
runtime version is '{3}' or higher.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0815

Article•11/25/2024

The source of a column cannot be a flow filter.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0817

Article•11/25/2024

Controls of type '{0}' are not allowed in the '{1}' area for pages of type '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0819

Article•11/25/2024

The {0} '{1}' already defines an event called '{2}' with the same parameter types in '{3}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0824

Article•11/25/2024

Field '{0}' is moved and cannot be used in an active key.

A moved field cannot be used in a key.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0825

Article•11/25/2024

Field '{0}' cannot be moved to {1} '{2}' because '{2}' is marked as Moved.

A field cannot be moved to a symbol that is already marked as Moved.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0827

Article•11/25/2024

Argument {0}: The argument {0} of field class {1} is not supported. Allowed field class
types are '{2}'.

For more information about field classes, refer to the property's documentation.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0828

Article•11/25/2024

The field '{0}' with ID '{1}' can't be moved because it is part of the table's primary key.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0829

Article•11/25/2024

Symbol of kind {0} '{1}' cannot be moved to its own app.

MovedTo/MovedFrom property cannot have Guid that matches its own AppId.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0831

Article•11/25/2024

The method '{0}' is not supported as the implementation for the interface method
because it is a try function.

Try functions cannot be used as interface method implementations because this can
lead to unexpected behavior from the runtime.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0832

Article•11/25/2024

Action area of type '{0}' is not valid in control '{1}' of type '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0833

Article•11/25/2024

{0} '{1}' cannot be defined outside an action area or group on this control type.

Only cue actions can be defined directly under the actions control.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0834

Article•11/25/2024

'MovedTo' property is required for a symbol of kind '{0}' {1} that has ObsoleteState set to
Moved or PendingMove.

When a symbol is prepared for moving or being moved the destination Application Id
must be specified in the 'MovedTo' property.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0838

Article•11/25/2024

The XLIFF file for text data could not be generated.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0839

Article•11/25/2024

The symbol '{0}' has same trans unit ID in Text Data XLIFF file as one or more other
symbols.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0840

Article•11/25/2024

The file extension '{0}' is not valid. Example of an expected value is '.app'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0841

Article•11/25/2024

The file extension '{0}' is already defined.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0843

Article•11/25/2024

The property '{0}' can only be used if the {1}'s type is '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0844

Article•11/25/2024

The property '{0}' can only be used if the {1}'s type is one of these values: '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0846 (Preview)

Article•11/25/2024

The {0} '{1}' is already being used. The EntityName and EntityNames property values
must be unique.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0847

Article•11/25/2024

'{0}' does not contain a definition for '{1}'.

The referenced element does not contain a definition for the referenced member.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL0999

Article•11/25/2024

Internal error: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1001

Article•11/25/2024

Source file '{0}' could not be found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1002

Article•11/25/2024

Error opening response file '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1006

Article•11/25/2024

Metadata file '{0}' could not be found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1007

Article•11/25/2024

Missing file specification for '{0}' option.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1008

Article•11/25/2024

Command-line syntax error: Missing '{0}' for '{1}' option.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1009

Article•11/25/2024

Unrecognized option: '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1010

Article•11/25/2024

Command-line syntax error: Missing :<number> for '{0}' option.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1012

Article•11/25/2024

Could not write to output file '{0}' -- '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1013

Article•11/25/2024

'{0}' is a binary file instead of a text file.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1014

Article•11/25/2024

Source file '{0}' could not be opened -- {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1015

Article•11/25/2024

Compilation canceled by user.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1017

Article•11/25/2024

The manifest file is not valid. {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1018

Article•11/25/2024

Directory '{0}' could not be found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1019

Article•11/25/2024

One or more dependencies defined in the project manifest are not valid. One or more of
the required attributes: 'publisher', 'name', 'version', and 'id' are either missing or not
valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1021

Article•11/25/2024

The package cache path has not been specified.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1022

Article•11/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be found in the package cache folders: {3}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1023

Article•11/25/2024

The package file {0} is not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1024

Article•11/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be loaded. {3}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1028

Article•11/25/2024

An IO exception has happened when trying to write to output file '{0}' -- '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1032

Article•11/25/2024

Translation file '{0}' has the same target language as another translation file.

There must be at most one translation file per language.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1033

Article•11/25/2024

An error occurred while loading the included rule set file {0} - {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1034

Article•11/25/2024

The link '{0}' must contain a placeholder with value 0 for the user locale.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1035

Article•11/25/2024

The manifest properties 'baseHelpUrl' and 'supportedLocales' must both be specified
and have values.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1036

Article•11/25/2024

The locale '{0}' is not valid.

A translation locale culture specified in the manifest must follow the format
languageCode-CountryCode, such as en-US.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1037

Article•11/25/2024

The locale '{0}' is already defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1038

Article•11/25/2024

The version number '{0}' for the property '{1}' does not match the expected format:
W.X.Y.Z where W, X, Y, and Z represent positive integers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1039

Article•11/25/2024

The version number '{0}' for the property '{1}' does not match the expected format: X.Y
where X and Y represent positive integers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1040

Article•11/25/2024

The guid number '{0}' does not match the expected pattern: "^[0-9a-fA-F]{{8}}-[0-9a-fA-
F]{{4}}-[0-9a-fA-F]{{4}}-[0-9a-fA-F]{{4}}-[0-9a-fA-F]{{12}}$".

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1041

Article•11/25/2024

The property '{0}' must be defined in the manifest.

The properties 'name', 'publisher','id' and 'version' must be defined in the manifest.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1042

Article•11/25/2024

The id '{0}' for the package with publisher '{1}', name '{2}', and version '{3}' specified in
the project manifest does not match the id '{4}' of the package with the same name,
publisher, and version found in the package cache folder.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1043

Article•11/25/2024

The runtime version '{0}' is not supported by the AL compiler.

The specified runtime version is not supported by the AL compiler. For more
information, see Currently available runtime versions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1044

Article•11/25/2024

The value for the manifest property '{0}' is not valid. Expected type: {1}.

Wrong type for a manifest property. For more information about manifest properties
and their type, see App.json file.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1045

Article•11/25/2024

The package cache {0} could not be found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1046

Article•11/25/2024

The application ID ranges {0} are overlapping.

An application cannot use overlapping ID ranges.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1047

Article•11/25/2024

The application ID range {0} is not valid.

A correct application ID range [startID..endID] must respect that startID > 0, endID > 0
and startID <= endID.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1048

Article•11/25/2024

Both 'idRange' and 'idRanges' properties are added. You should use the 'idRanges'
property and remove the 'idRange' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1049

Article•11/25/2024

A project without a manifest must have the /out option specified.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1050

Article•11/25/2024

Fast publishing requires an application file '{0}' to be build and published.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1051

Article•11/25/2024

Fast publishing requires that there are no manifest changes for the application '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1052

Article•11/25/2024

The link '{0}' can only contain one placeholder with value 0 for the user locale. No other
placeholder values are allowed.

A help URL can only contain one placeholder for the user locale, which must have the
value 0.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1053

Article•11/25/2024

The value '{0}' is not valid for the manifest property '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1054

Article•11/25/2024

Invalid reference module: {0}. Please clear the downloaded symbols cache and re-
download symbols.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1057

Article•11/25/2024

The module specification is not valid. One or more of the required attributes: 'publisher',
'name', and 'id' are either missing or not valid.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1060

Article•11/25/2024

The max degree of parallelism must be -1 or positive.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1061

Article•11/25/2024

An error occurred during file validation: '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1062

Article•11/25/2024

Too many key vault URLs specified.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1063

Article•11/25/2024

Key vault URL is too long.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1064

Article•11/25/2024

Key vault URL is not a valid Azure key vault URL. A valid key vault URL must use HTTPS
and point to the Azure key vault domain.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1065

Article•11/25/2024

Key vault URL should not have a path or query string.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1066

Article•11/25/2024

Duplicate package dependency with application ID '{0}', publisher '{1}', and name '{2}'.
Remove duplicate dependencies in the application manifest.

Multiple package dependencies with the same application ID, publisher and name have
been defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1067

Article•11/25/2024

Duplicate package dependency with publisher '{0}', and name '{1}'. Remove duplicate
dependencies in the application manifest.

Multiple package dependencies with the same publisher and name have been defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1068

Article•11/25/2024

Duplicate package dependency with application ID '{0}', and publisher '{1}'. Remove
duplicate dependencies in the application manifest.

Multiple package dependencies with the same application ID and publisher have been
defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1069

Article•11/25/2024

Duplicate package dependency with application ID '{0}', and name '{1}'. Remove
duplicate dependencies in the application manifest.

Multiple package dependencies with the same application ID and name have been
defined.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1070

Article•11/25/2024

Duplicate package dependency with application ID '{0}'. Remove duplicate dependencies
in the application manifest.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1071

Article•11/25/2024

Error writing to XML documentation file: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1073

Article•11/25/2024

The procedure with name {0} has the same name as a declared trigger.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1074

Article•11/25/2024

Both 'applicationInsightsKey' and 'applicationInsightsConnectionString' are added. You
should use the 'applicationInsightsConnectionString' property and remove the
'applicationInsightsKey' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1075

Article•11/25/2024

Both 'ShowMyCode' and 'ResourceExposurePolicy' properties are added. You should use
the 'ResourceExposurePolicy' property and remove the 'ShowMyCode' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1077

Article•11/25/2024

An error was encountered when trying to load the workspace: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1081

Article•11/25/2024

Unable to update report layout '{0}' for '{1}'. Reason: {2}.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1082

Article•11/25/2024

The manifest property '{0}' is only available for Target '{1}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1130

Article•11/25/2024

The format of property '{0}' must be a timeout duration specified as
'[d.]hh:mm:ss[.fffffff]'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1150

Article•11/25/2024

The link in parameter '{0}' ({1}) is not valid. {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1151

Article•11/25/2024

Cannot create a manifest for Extension "{0}" because the Name and Publisher match the
current application. Remove this dependency from the application manifest.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1152

Article•11/25/2024

Dependency with ID '{0}' matches the current application ID. Remove this dependency
from the application manifest.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1153

Article•11/25/2024

The referenced module '{1}' with runtime reference version '{0}' cannot be loaded by the
compiler with version '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1154

Article•11/25/2024

It is not possible to specify both '{0}' and '{1}' at the same time.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Error AL1155

Article•11/25/2024

Missing folder specification for '{0}' option.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0200

Article•11/25/2024

Property '{0}' is obsolete and will be removed in a future version.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0235

Article•11/25/2024

The expression CONST() on the option value '{0}' is obsolete. Use CONST(" ") to refer to
the empty option value.

The expression CONST() as an option value is obsolete. Use CONST(" ") to refer to the
empty option value.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0251

Article•11/25/2024

Application object '{0}' is missing.

The specified object is not found.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0254

Article•11/25/2024

Sorting field '{0}' should be part of the keys for table '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0374

Article•11/25/2024

The use of a unique ID has been deprecated and the ID can be removed.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0424

Article•11/25/2024

The multilanguage syntax should not be used because the app uses translation files (the
"features" property of the app.json includes "TranslationFile"). Update the translation
files and use the label syntax instead.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0432

Article•11/25/2024

{0} '{1}' is marked for removal. {2}.

The referenced object will become obsolete.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0457

Article•11/25/2024

The label syntax is not correct. Please move the '{0}' to its designated attribute.

Use the correct label syntax as specified in Label Syntax.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0467

Article•11/25/2024

Cannot access file '{0}'. The file is most likely read-only.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0472

Article•11/25/2024

The source of the translation item does not match the label value. Ignoring the
translation item.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0473

Article•11/25/2024

The translated string of the translation item is too long. Trimming the translated string.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0479

Article•11/25/2024

There must be only one translation item for each ID.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0482

Article•11/25/2024

The image {0} is not valid in this context.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0483

Article•11/25/2024

The property Image cannot be used on nested Action Groups inside the 'Sections' area.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0509

Article•11/25/2024

Constant value '{0}' is outside of the valid ordinal range for this option type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0520

Article•11/25/2024

{0} '{1}' is removed. {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0557

Article•11/25/2024

The name of the codeunit local variable '{0}' is identical to a field in table '{1}' and will
shadow that table field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0558

Article•11/25/2024

The name of the codeunit global variable '{0}' is identical to a field in table '{1}'.

The name of the codeunit global variable should be different from the name of any
table field.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0567

Article•11/25/2024

The field '{0}' is using the same name as a system-provided field and will shadow that
field.

A field should use a different name from a system-provided field's name.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0588

Article•11/25/2024

The type of parameter '{1}' on event subscriber '{0}' is of type 'Option', but the expected
type is '{2}'. Please update the subscriber type to match the publisher.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0592

Article•11/25/2024

Compatibility: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0603

Article•11/25/2024

An implicit conversion is being performed from a value of type '{0}' to a value of type
'{1}'. This conversion can lead to unexpected runtime issues.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0609

Article•11/25/2024

Adding actions to CueGroups is not supported.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0610

Article•11/25/2024

Moving actions in CueGroups is not supported.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0611

Article•11/25/2024

Modifying actions in CueGroups is not supported.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0626

Article•11/25/2024

Expected identifier or numeric literal.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0627

Article•11/25/2024

Expected 'disable' or 'restore' keyword.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0628

Article•11/25/2024

Unrecognized #pragma directive.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0633

Article•11/25/2024

Expected 'disable', 'enable' or 'restore' keyword.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0634

Article•11/25/2024

Single-line comment or end-of-line expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0640

Article•11/25/2024

XML comment has badly formed XML -- '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0641

Article•11/25/2024

Parameter '{0}' has no matching param tag in the XML comment for '{1}' (but other
parameters do).

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0642

Article•11/25/2024

Missing XML comment for publicly visible type or member '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0643

Article•11/25/2024

XML comment is not placed on a valid language element.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0644

Article•11/25/2024

XML comment has a param tag for '{0}', but there is no parameter by that name.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0645

Article•11/25/2024

XML comment on '{1}' has a paramref tag for '{0}', but there is no parameter by that
name.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0646

Article•11/25/2024

XML comment has a duplicate param tag for '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0647

Article•11/25/2024

{0}. See also error AL{1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0659

Article•11/25/2024

The length of the enum identifier '{0}' should not exceed {1} characters as it may result in
runtime issues in cases where there are other enums with the same first {1} characters.

The length of an enum identifier should not exceed 30 characters.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0679

Article•11/25/2024

The application object '{0}' is not included in any entitlement and will therefore not be
accessible in the cloud.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0684

Article•11/25/2024

The permissionset '{0}' contains permissionsets or permission for objects from other
module. Permissions on objects from other modules will be ignored.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0717

Article•11/25/2024

The property 'CalcFormula' is required for the field '{0}' in {1} '{2}' because the field's
property 'FieldClass' is set to 'FlowField'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0739

Article•11/25/2024

The name of {0} '{1}' cannot be empty.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0748

Article•11/25/2024

The return type '{0}' of the {1} method '{2}' has 'Internal' accessibility. The return value
will not be usable outside of this module without an implicit conversion.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0749

Article•11/25/2024

The type '{0}' of the parameter '{1}' of the {2} method '{3}' has 'Internal' accessibility. The
method will not be callable outside of this module without an implicit conversion.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0756

Article•11/25/2024

The division by Abs(integer) will change its behavior in release version 11. For more
information visit the official documentation.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0773

Article•11/25/2024

The number of files found in '{0}' exceeds {1}. This may result in a slower compilation.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0789

Article•11/25/2024

Using directives are ignored if a namespace is not specified.

Using directive are ignored if a namespace is not specified.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0790

Article•11/25/2024

The using directive for '{0}' appeared previously in this namespace declaration.

The namespace in the using directive is already included in the namespace declaration.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0796

Article•11/25/2024

The 'Unwrap' method should only be used inside a non-debuggable method otherwise
the contents of the value will be viewable through the debugger.

The 'Unwrap' method should only be used inside a non-debuggable method otherwise
the contents of the value will be viewable through the debugger.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0801

Article•11/25/2024

{0} '{1}' is marked to be moved. {2}.

The referenced object has been marked as obsolete pending move. That is, the owner of
the extension that defines it will move it in a future version.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0807

Article•11/25/2024

The integer '{0}' should not be used as the name for the object.

Integers should not be used as the names of objects because they prevent referencing
the object by name.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0820

Article•11/25/2024

{0} '{1}' is missing.

Cannot resolve the referenced application object.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0821

Article•11/25/2024

The method '{0}' is missing or does not have exactly one parameter of type {1}.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0822

Article•11/25/2024

'{0}' is an ambiguous reference between '{1}' defined by the extension '{2}' and '{3}'
defined by the extension '{4}'.

Ambiguous reference between two symbols.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0823

Article•11/25/2024

Field '{0}' is marked as PendingMove and cannot be used in an active key.

A field with ObsoleteState PendingMove cannot be used in a key.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0835

Article•11/25/2024

The LayoutFile '{0}' is already being used. To avoid build issues, a layout file shouldn't be
updated by different layouts.

To avoid build issues, a layout file shouldn't be updated by different layouts. Each layout
file should only be used in a single layout.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0836

Article•11/25/2024

The {0} '{1}' contains a reference to the field '{2}' which is defined in another object from
the same app. If you are preparing to move this object to another extension in the
future, this reference will be an issue.

Fields from other object from the same app cannot be referenced as it would cause
issues if you are splitting the objects to prepare a future move to another extension.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0842

Article•11/25/2024

The type '{0}' of the {1} field '{2}' has 'Internal' accessibility. The field will not be usable
outside of this module without an implicit conversion.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL0848

Article•11/25/2024

'{0}' is a keyword from version '{1}'.

The identifier {0} has become a keyword in version {1}.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1000

Article•11/25/2024

Ignoring /noconfig option because it was specified in a response file.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1003

Article•11/25/2024

An instance of analyzer {0} cannot be created from {1} : {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1004

Article•11/25/2024

The assembly {0} does not contain any analyzers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1005

Article•11/25/2024

Unable to load Analyzer assembly {0} : {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1011

Article•11/25/2024

Source file '{0}' specified multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1025

Article•11/25/2024

The file at location '{0}' does not match any definition.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1026

Article•11/25/2024

A warning occurred during XML validation: '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1029

Article•11/25/2024

Translation file '{0}' has invalid target language '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1030

Article•11/25/2024

Translation file '{0}' is missing a target language.

A translation file must specify a target language.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1055

Article•11/25/2024

Invalid reference module: {0}. Please clear the downloaded symbols cache and re-
download symbols.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1056

Article•11/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be loaded. {3}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1058

Article•11/25/2024

appId and Id are both specified for a dependency property. The appId value will be
ignored.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1059

Article•11/25/2024

Feature '{0}' can only be enabled, if feature '{1}' is also enabled.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1072

Article•11/25/2024

The name for the preprocessing symbol is not valid; '{0}' is not a valid identifier.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning AL1156

Article•11/25/2024

Comments are not recommended inside the manifest file as they can cause
interoperability issues with CI/CD pipelines or other integrations.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0269

Article•11/25/2024

The referenced page '{0}' should be a list part or a card part.

A page used as a page part should be a list part or a card part.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0273

Article•11/25/2024

The name '{0}' is an Area type. Using an Area type name will limit extensibility as
dependent extension won't be able to reference it.

Reusing the Area type as the name of a control, action, or variable might lead to
extensibility limitations.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0299

Article•11/25/2024

Member name '{0}' is only allowed on triggers.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0468

Article•11/25/2024

Length of the table field name '{0}' must not exceed {1} characters. Longer field names
are prone to cause SQL errors.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0481

Article•11/25/2024

The property Image can only be used on fields that are contained in a CueGroup
control.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0486

Article•11/25/2024

A member of type {0} with name '{1}' is already defined in {2} '{3}' by the extension '{4}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0493

Article•11/25/2024

The RunObject property value of actions defined in the '{0}' area must only reference
pages of type 'List'.

The **RunObject** property value must only reference pages of type 'List'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0523

Article•11/25/2024

The {0} '{1}' already defines a method called '{2}' with the same parameter types in '{3}'.

A method is defined multiple times.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0524

Article•11/25/2024

The base type already defines a method called '{0}' with the same parameter types.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0534

Article•11/25/2024

Length of the table key name '{0}' must not exceed {1} characters. Longer key names are
prone to cause SQL errors.

The length of a table key name must not exceed 28 characters. Longer key names are
prone to cause SQL errors.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0545

Article•11/25/2024

An area of type '{0}' is not valid on pages of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0547

Article•11/25/2024

The event '{0}' should not expose global variables.

An event publisher should not expose global variables.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0548

Article•11/25/2024

Cannot move symbol '{0}' from '{1}' area to '{2}' area.

Cannot move a symbol between areas.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0550

Article•11/25/2024

Groups defined in the action area '{0}' should only contain actions.

Groups defined in an action area should only contain actions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0551

Article•11/25/2024

The action area '{0}' can only contain actions.

An action area can only directly contain groups.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0552

Article•11/25/2024

The action area '{0}' can only directly contain groups.

An action area can only directly contain groups.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0556

Article•11/25/2024

The RunObject property value of actions defined in the '{0}' area must only reference
objects of type {1}.

The **RunObject** property value must only reference objects of type 'Codeunit', 'Page',
'Report', or 'XmlPort'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0559

Article•11/25/2024

A Part type page cannot contain other parts.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2020 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0560

Article•11/25/2024

Only parts and groups are valid in an area of type 'RoleCenter'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0561

Article•11/25/2024

Only parts are valid in an area of type 'FactBoxes'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0562

Article•11/25/2024

The value assigned to the SystemPart type is not valid. Valid values are {0}.

The value assigned to the SystemPart type must be Notes, Links, MyNotes or Outlook.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0563

Article•11/25/2024

A control of type '{0}' is not allowed in a parent control of type '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0568

Article•11/25/2024

Groups defined in the action area '{0}' should only contain actions or groups.

Groups defined in an action area should only contain actions or groups.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0569

Article•11/25/2024

A page of type Role Center cannot have procedures.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0571

Article•11/25/2024

The property 'Description' should only be used for internal comments. Use the property
'Caption' or 'CaptionML' in order to specify the profile caption displayed to end users.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0573

Article•11/25/2024

{0} is not valid for client expressions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0586

Article•11/25/2024

The identifier contains characters that are not valid: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0589

Article•11/25/2024

The name '{0}' is used across multiple columns and data items. This will prevent
extensibility of this column or data item.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0590

Article•11/25/2024

The property {0} is only supported on {1}.

The referenced property is not supported on the element is was set on. For more
information on the elements the property applies to, refer to the property's
documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0593

Article•11/25/2024

The type of the parameter '{0}' on the event subscriber '{1}' has a smaller capacity than
the parameter type '{2}' on the publisher.

The capacity of the type of a parameter on an event subscriber is smaller than the
capacity of type of the same parameter on the publisher, which will lead to a lossy
conversion.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0598

Article•11/25/2024

Cannot move or modify the {0} '{1}' in the same '{2}' that you added.

Cannot move or modify an element in the same object extension that you added it.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0600

Article•11/25/2024

The property '{0}' can only be set on elements of type Option.

The properties **OptionCaption** , **OptionMembers** , **OptionCaptionML** and
**OptionOrdinalValues** cna only be set on elements of the type Option.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0601

Article•11/25/2024

{0} '{1}' is removed. {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0602

Article•11/25/2024

'{0}' is inaccessible due to its protection level.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0604

Article•11/25/2024

Use of implicit 'with' will be removed in the future. Qualify with '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0606

Article•11/25/2024

The 'with' statement is deprecated and will be removed for cloud development in a
future release.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0608

Article•11/25/2024

The OrderBy property must specify at least one field on which to sort the data.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0613

Article•11/25/2024

Wrong signature. Correct signature for '{0}' is '{1}'.

Invalid signature for trigger. For more information about the correct signature, refer to
the trigger's documentation.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2021 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0614

Article•11/25/2024

The value '{0}' is not allowed for property '{1}'.

The value used as a property value is reserved.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0615

Article•11/25/2024

Field '{0}' is not specified as a source expression on page '{1}'. All fields specified in
ODataKeyFields must be used as the source expression in a page control.

All fields specified in the **ODataKeyFields** property must be used as the source
expression in a control of the page that specifies them.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0617

Article•11/25/2024

Event trigger 'OnBeforeActionEvent' cannot be used because the action '{0}' specifies
the 'RunObject' property.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0635

Article•11/25/2024

A method with 'OnPrem' scope cannot be used as event subscriber. It will fail at runtime
when the publisher has 'Cloud' scope.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0639

Article•11/25/2024

'Variant' is not a valid column type for column '{0}' in report '{1}'.

A report column must not be of the type 'Variant'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2021 release wave 1.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0649

Article•11/25/2024

Comma is not supported in enum value names or in captions. Enum Value = '{0}',
Property = '{1}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0650

Article•11/25/2024

The text with a length of {0} is longer than the MaxLength of {1} which means that the
text will be trimmed.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0655

Article•11/25/2024

The property DataItemLinkReference can only refer to an ancestor DataItem.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0660

Article•11/25/2024

The property '{0}' cannot be customized.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2022 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0667

Article•11/25/2024

'{0}' is being deprecated in the versions: {1} {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0677

Article•11/25/2024

The member '{0}' in object '{1}' cannot be declared as protected in object type '{2}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2022 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0685

Article•11/25/2024

The length '{0}' of the calculation formula's target field '{1}' is greater than the length
'{2}' of the source flow field '{3}'. This could result in a runtime error. Please make sure
that the target field's length is less than equal to the source field length.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0692

Article•11/25/2024

The primary key '{0}' on table '{1}' cannot be obsolete. All related properties will have no
effect.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2022 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0694

Article•11/25/2024

The field '{0}' which is part of the primary key of table '{1}' cannot be obsolete. All
related properties will have no effect.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2022 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0695

Article•11/25/2024

The method {0} will only be available for {1} development for runtime version {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0697

Article•11/25/2024

Argument {0}: The argument should be a valid Field type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0700

Article•11/25/2024

Dependency '{0}' must be referenced in the property '{1}' rather than as an explicit
dependency.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0702

Article•11/25/2024

Dependency '{0}' is referenced in the property '{1}' and as an explicit dependency.
Remove the explicit dependency.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0711

Article•11/25/2024

A member of type {0} with name '{1}' is already defined in {2} '{3}' by the extension '{4}'.
Duplicate member names are not allowed when defining CueActions.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0715

Article•11/25/2024

The {0} name '{1}' is reserved for future AL language features.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2022 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0727

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0728

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set to '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0729

Article•11/25/2024

The {0} '{1}' can only be used if the property '{2}' is set with any of the values of: '{3}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0731

Article•11/25/2024

The name '{0}' does not exist in the current context.

The referenced name does not exist in the current context.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0733

Article•11/25/2024

Access modifier '{0}' is not allowed for member '{1}' in the context of object type '{2}'.

The access modifier is not allowed for the declared member in the context of the
containing type.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0743

Article•11/25/2024

The property '{0}' is not valid for action '{1}' defined in control '{2}' of type '{3}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0745

Article•11/25/2024

The property '{0}' is not valid for action '{1}' defined in a report request page.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0751

Article•11/25/2024

Enum values can't be nested. Use '{0}' instead.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0753

Article•11/25/2024

The name of a dataitem cannot be empty because it can cause runtime errors.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0755

Article•11/25/2024

The '{0}' already defines a built-in member called '{1}'. Choose another name for {2} '{1}',
or it might cause runtime issues.

A built-in member with the same name is already defined for the object, which can
cause runtime errors.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0758

Article•11/25/2024

The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the extension '{5}'.
Choose another name for one of them. Otherwise, this might cause runtime issues.

White spaces in names are internally replaced with an underscore during compilation, so
that two different names can collide.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0768

Article•11/25/2024

The property '{0}' is required when property '{1}' is set to '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0769

Article•11/25/2024

The property '{0}' is required.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0775

Article•11/25/2024

Try methods should not specify an explicit return value, because the value will be
discarded. The actual return value depends on whether the method returns an error or
not.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0778

Article•11/25/2024

The implicit conversion will overflow when converting from a 'Guid' to a '{0}' which is
shorter than the converted textual representation of a 'Guid'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0780

Article•11/25/2024

It is not allowed to assign a value to a field of FieldClass='{0}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0782

Article•11/25/2024

A page extension is only allowed to access control add-ins defined within its own
extension scope.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0788

Article•11/25/2024

An area of type '{0}' is only valid on pages of type(s) '{1}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0803

Article•11/25/2024

The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the extension '{5}'.
Choose another name for one of them. Otherwise, this might cause runtime issues.

White spaces in names are internally replaced with an underscore during compilation, so
that two different names can collide. This diagnostic is specific to event and event
subscriber methods.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0804

Article•11/25/2024

You cannot reference the {0} '{1}' because it is defined in the page customization '{2}'.

You cannot reference an element defined in a page customization outside the page
customization declaring it.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0805

Article•11/25/2024

The object ID '{0}' should not be surrounded with quotes.

Quoted identifiers should not be used to specify object IDs. Integer literals should be
used instead.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0814

Article•11/25/2024

The source of a column cannot be a flow filter.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0816

Article•11/25/2024

The property '{0}' cannot be set if the property '{1}' is set to '{2}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0818

Article•11/25/2024

The {0} '{1}' already defines an event called '{2}' with the same parameter types in '{3}'.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0826

Article•11/25/2024

The type '{0}' cannot be used as a type argument in this context.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0830

Article•11/25/2024

The method '{0}' is not supported as the implementation for the interface method
because it is a try function.

Try functions cannot be used as interface method implementations because this can
lead to unexpected behavior from the runtime.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2024 release wave 2.
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0837

Article•11/25/2024

The symbol '{0}' results in the same translation ID as one or more other symbols.
Rename symbol to resolve the problem.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL0845

# (Preview)

Article•11/25/2024

The {0} '{1}' is already being used. The EntityName and EntityNames property values
must be unique.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2025 release wave 1.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Warning (Future Error) AL1078

Article•11/25/2024

Key vault URL is not a valid Azure key vault URL. A valid key vault URL must use HTTPS
and point to the Azure key vault domain.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
```
） Important
```
```
This warning will become an error with Business Central 2023 release wave 2.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Hidden AL0605

Article•11/25/2024

Use of implicit 'with' will be removed in the future. Qualify with '{0}'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Hidden AL0607

Article•11/25/2024

The 'with' statement is deprecated and will be removed for cloud development in a
future release.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Hidden AL0792

Article•11/25/2024

Unused using directive '{0}'.

The using directive is not used.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL0678

Article•11/25/2024

The name of {0} '{1}' conflicts with {0} '{2}' defined in {3} '{4}' by the extension '{5}'.
Choose another name for one of them. Otherwise, this might cause runtime issues.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL0719

Article•11/25/2024

Argument {0}: The argument should be a valid Field type. An argument of type Joker or
Variant might have an underlying type that is not a valid Field type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL1031

Article•11/25/2024

Successfully included translations for: {0}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL1076

Article•11/25/2024

A package that satisfies the dependency on app with ID {0} with name '{1}' and publisher
'{2}' was found, but the name or publisher has changed. New name '{3}' and new
publisher '{4}'. Consider updating the dependency reference to the new name/publisher.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL1079

Article•11/25/2024

Debugging will not work for this extension because 'allowDebugging' has been set to
false and 'applyToDevExtension' to true.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Information AL1080

Article•11/25/2024

Source will still be visible for this extension via debugging because 'allowDebugging'
has been set to true.

For more information, see Resource Exposure Policy Setting.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Fatal Error AL1100

Article•11/25/2024

File name '{0}' is empty, contains invalid characters, has a drive specification without an
absolute path, or is too long.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Fatal Error AL1101

Article•11/25/2024

Target must specify one of: 'internal', 'solution', 'extension'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1401

Article•11/25/2024

Reference '{0}' in application object '{1}' does not exist.

Cannot resolve the type of the referenced element.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1402

Article•11/25/2024

{0} '{1}' is missing.

Cannot resolve the referenced application object.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1403

Article•11/25/2024

'{0}' is an ambiguous reference between '{1}' defined by the extension '{2}' and '{3}'
defined by the extension '{4}'.

Cannot resolve an element because it has been declared in multiple extensions. The
customization is discarded.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1404

Article•11/25/2024

The action '{0}' is not found in the target '{1}'.

Cannot resolve a reference to an action in a page extension or page customization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1405

Article•11/25/2024

The control '{0}' is not found in the target '{1}'.

Cannot resolve a reference to a control in a page extension or page customization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1406

Article•11/25/2024

The view '{0}' is not found in the target '{1}'.

Cannot resolve a reference to an view in a page extension or page customization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1407

Article•11/25/2024

At least one target has to be specified for the move.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1408

Article•11/25/2024

Invalid application object identifier. A number or an application object name is expected.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1409

Article•11/25/2024

Page '{0}' should be of type 'RoleCenter'.

The page used as a Role Center for a profile or profile extension is not a page of type
'RoleCenter'.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1410

Article•11/25/2024

The target {0} '{1}' for the extension object is not found.

Cannot resolve the referenced target of a page customization or the target of a profile
extension.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1411

Article•11/25/2024

Multiple page customizations have been specified for the same page {0} within the same
profile.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1412

Article•11/25/2024

{0} '{1}' is marked for removal. {2}.

The referenced object has been marked as obsolete pending. That is, the owner of the
extension that defines it will remove it in a future version.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1413

Article•11/25/2024

A member of type {0} with name '{1}' is already defined in {2} '{3}' by the extension '{4}'.

Another extension has defined a page element with the same name as the one declared
in the user personalization or profile configuration.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1415

Article•11/25/2024

{0} '{1}' is removed. {2}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1418

Article•11/25/2024

A DataItem with name '{0}' could not be found in the target {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1419

Article•11/25/2024

A DataItem or Column with name '{0}' could not be found in the target {1}.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1420

Article•11/25/2024

The {0} '{1}' cannot be used as target of the ActionRef '{2}'. ActionRefs can only target
Actions. Ignoring the ActionRef.

ActionRefs can only target actions of type Action.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1421

Article•11/25/2024

The {0} '{1}' is using the '{2}' property. This will be automatically converted to the new
syntax when customizing the related page in the webclient.

Code referencing the Promoted properties should be replaced by actionref syntax.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1422

Article•11/25/2024

The target action '{0}' cannot be resolved in page '{1}'. Ignoring the ActionRef.

This can cover both the RunObject or the ActionTarget.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1423

Article•11/25/2024

'{0}' does not contain a definition for '{1}'.

The referenced element does not contain a definition for the referenced member.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1424

Article•11/25/2024

The name '{0}' does not exist in the current context.

The referenced name does not exist in the current context.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Warning AL1425

Article•11/25/2024

The field with ID '{0}' and name '{1}' cannot be used as source expression in the page
customization '{2}' targeting page '{3}'. Ignoring the page field.

Getting Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Information AL1414

Article•11/25/2024

The page customization for page '{0}' does not make any modifications, so it can be
removed without affecting any profiles or user personalization.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Information AL1416

Article•11/25/2024

The {0} '{1}' cannot be moved relatively to '{2}' because '{2}' is missing. This move is
ignored.

An element (action, control or view) cannot be moved relative to an anchor (action,
control or view) that cannot be resolved because its declaring extension is not installed
anymore. The change is ignored.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Compiler Designer Customization

# Information AL1417

Article•11/25/2024

The {0} '{1}' cannot be added relatively to '{2}' because '{2}' is missing. '{1}' is added at a
default location instead.

The anchor of an add (action or view) cannot be resolved because its declaring
extension is not installed anymore. The elements are added into a default location.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help.
Thanks!
```
## Description

## Related information

```
 Yes  No
```

# Application Validation Service

# diagnostics overview

Article•04/26/2024

When an app is submitted for AppSource, a per-tenant extension is submitted, or when
a tenant is about to be upgraded, the Application Validation Service is run. This article
gives an overview of the diagnostics that running the AVS tool gives, sorted by ID and
severity. For more information about a specific diagnostic, choose the ID.

```
ID Message Default
Severity
AVS0001 The 'app.json' could not be found in the specified package. Error
```
```
AVS0002 The runtime version '{0}' of the extension is too recent for the release of
Business Central being validated. The latest supported runtime version is
'{1}'.
```
```
Error
```
```
AVS0003 The file '{0}' could not be added to the file system because a file with the
same name already exists.
```
```
Error
```
```
AVS0004 The specified ruleset could not be loaded. Details: {0} Error
AVS0005 A package with publisher '{0}', name '{1}', and a version compatible with
'{2}' could not be found.
```
```
Error
```
```
AVS0006 The runtime version '{0}' is not supported for the release '{1}' because its
latest supported runtime version is '{2}'.
```
```
Error
```
```
AVS0007 The release version '{0}' is not supported. Error
AVS0101 A package with publisher '{0}', name '{1}', and a version compatible with
'{2}' could not be found.
```
```
Error
```
```
AVS0102 A package with publisher '{0}', name '{1}', and a version compatible with
'{2}' could not be loaded.
```
```
Error
```
```
AVS0103 The extension with ID '{0}' appears multiple times in the submission, while
all extensions submitted are expected to have a unique ID.
```
```
Error
```
```
AVS0104 The extension '{0}' by '{1}' (version '{2}') is a runtime package, which is not
allowed in Business Central online.
```
```
Error
```
```
AVS0105 The submission must target at least one existing release of Business
Central. Verify the dependencies specified in the app.json of all the apps
submitted. For more information about the target release computation,
```
```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
ID Message Default
Severity
see the examples in the Technical Validation Checklist at
https://aka.ms/CheckBeforeYouSubmit.|Error|
AVS0106 The submission must target at least one existing country/region of
Business Central. Verify that at least one country/region is marked as
'Available' at aka.ms/bccountries. For more information, see the Technical
Validation FAQ, at https://go.microsoft.com/fwlink/?linkid=2182737.|Error|
AVS0107 The extension '{0}' by '{1}' (version '{2}') has already been uploaded to
Business Central for the country/region '{3}' with different content. Remove
this extension from your submission, use the same .app file as the one that
has already been uploaded to Business Central, or increase the version in
the app.json. For more information, see the Technical Validation FAQ, at
https://go.microsoft.com/fwlink/?linkid=2182737.|Error|
AVS0108 The following extension(s) could not be found. Upload the missing
extensions and try again. {0}.
```
```
Error
```
```
AVS0109 The per-tenant extension (or one of its dependencies) cannot be deployed
as it has missing dependencies or the dependencies are conflicting with
currently installed apps. Check if these dependencies are installed.
```
```
Error
```
```
AVS0110 A {0} with ID {1} is found in both {2} and {3}. Object IDs must be unique per
environment. Resolve the conflict in your extension by using a different ID
and upload the extension again.
```
```
Warning
```
```
AVS0111 A {0} with name '{1}' is found in both {2} and {3}. Object names must be
unique per environment. Resolve the conflict in your extension by using a
different name and upload the extension again.
```
```
Warning
```
```
AVS0112 A {0} with ID {1} in '{2}' is found in both {3} and {4}. {0} IDs must be unique
within the base objects and their extension objects. Resolve the conflict in
your extension by using a different ID and upload the extension again.
```
```
Warning
```
```
AVS0113 A {0} with name '{1}' in '{2}' is found in both {3} and {4}. {0} names must be
unique within the base objects and their extension objects. Resolve the
conflict in your extension by using a different name and upload the
extension again.
```
```
Warning
```
```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0001

Article•10/25/2024

The 'app.json' could not be found in the specified package.

Rebuild the app either from Visual Studio Code or by using the alc.exe tool.

Get started with AL
Developing extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0002

Article•10/25/2024

The runtime version '{0}' of the extension is too recent for the release of Business Central
being validated. The latest supported runtime version is '{1}'.

In the app.json file of the app you must specify the latest supported runtime version or
lower. For more information, see app.json file and Choosing Runtime Version in AL.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0003

Article•10/25/2024

The file '{0}' could not be added to the file system because a file with the same name
already exists.

Something went wrong when compiling the app. Retry the operation and contact
Partner Center support if it fails again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0004

Article•10/25/2024

The specified ruleset could not be loaded. Details: {0}

Something went wrong when loading a ruleset, retry the operation and contact Partner
Center support if it fails again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0005

Article•10/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be found.

Validate that the dependency information is correct and that the dependencies are
available for the countries/releases validated.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostics?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0006

Article•10/25/2024

The runtime version '{0}' is not supported for the release '{1}' because its latest
supported runtime version is '{2}'.

In the app.json file of the app you have to specify the latest supported runtime version
or lower. For more information, see app.json file and Choosing Runtime Version in AL.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0007

Article•10/25/2024

The release version '{0}' is not supported.

In the app.json file of the app you must specify one of the supported runtime versions
from Choosing Runtime Version in AL.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0101

Article•10/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be found.

Validate that the dependency information is correct and that the dependencies are
available for the countries/regions and releases that are validated.

Technical Validation FAQ Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0102

Article•10/25/2024

A package with publisher '{0}', name '{1}', and a version compatible with '{2}' could not
be loaded.

Retry the operation and contact Partner Center support if it fails again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0103

Article•10/25/2024

The extension with ID '{0}' appears multiple times in the submission, while all extensions
submitted are expected to have a unique ID.

Make sure you only include your app once in the submission in Partner Center.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic for App Source

## submissions?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0104

Article•10/25/2024

The extension '{0}' by '{1}' (version '{2}') is a runtime package, which is not allowed in
Business Central online.

Runtime packages are not allowed. A new non-runtime package must be submitted. For
more information, see Runtime packages limitations.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0105

Article•10/25/2024

The submission must target at least one existing release of Business Central. Verify the
dependencies specified in the app.json file of all the apps submitted. For more

information about the target release computation, see the examples in the Technical
Validation Checklist.

The app.json files has a dependency either from the application property or the

dependencies section that sets the requirement higher than the available releases of
Business Central. To learn more see Technical Validation FAQ.

Choosing Runtime Version in AL Get started with AL Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0106

Article•10/25/2024

The submission must target at least one existing country/region of Business Central.
Verify that at least one country/region is marked as 'Available' at aka.ms/bccountries.
For more information, see the Technical Validation FAQ.

Technical Validation FAQ Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0107

Article•10/25/2024

The extension '{0}' by '{1}' (version '{2}') has already been uploaded to Business Central
for the country/region '{3}' with different content. Remove this extension from your
submission, use the same .app file as the one that has already been uploaded to
Business Central, or increase the version in the app.json file. For more information, see

Technical Validation FAQ.

Technical Validation Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0108

Article•10/25/2024

The following extension(s) could not be found. Upload the missing extensions and try
again. {0}.

The app has a dependency on one or more apps that are missing. Make sure all the
dependencies of the app is installed and retry the operation again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Error AVS0109

Article•10/25/2024

The per-tenant extension (or one of its dependencies) cannot be deployed as it has
missing dependencies or the dependencies are conflicting with currently installed apps.
Check if these dependencies are installed.

A common reason for this error is that a build already has been published directly from
Visual Studio Code in DEV scope.

Get started with AL
Developing extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Warning AVS0110

Article•10/25/2024

A {0} with ID {1} is found in both {2} and {3}. Object IDs must be unique per environment.
Resolve the conflict in your extension by using a different ID and upload the extension
again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Warning AVS0111

Article•10/25/2024

A {0} with name '{1}' is found in both {2} and {3}. Object names must be unique per
environment. Resolve the conflict in your extension by using a different name and
upload the extension again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Warning AVS0112

Article•10/25/2024

A {0} with ID {1} in '{2}' is found in both {3} and {4}. {0} IDs must be unique within the
base objects and their extension objects. Resolve the conflict in your extension by using
a different ID and upload the extension again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AVS Warning AVS0113

Article•10/25/2024

A {0} with name '{1}' in '{2}' is found in both {3} and {4}. {0} names must be unique within
the base objects and their extension objects. Resolve the conflict in your extension by
using a different name and upload the extension again.

Get started with AL
Developing Extensions

```
７ Note
```
```
The AL diagnostics topics are in preview. If you have input for this topic, we'd love
to hear from you. Use our GitHub repo to create a PR and add content to this topic
by going to here. To read about contributing, see Contribute to the Help. If
you'd like to see us prioritize certain areas within the AL diagnostics, you can file a
GitHub issue, in the Feedback section at the bottom of this page, choose This
page , fill in the template, and include REF PRI in the title. Thanks!
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0001

Article•10/01/2024

There must be exactly one space character on each side of a binary operator such as :=
+ - AND OR =.

There must be exactly one space character on each side of a binary operator such as :=
+ - AND OR =. The parameter comma operator however, should have no spaces.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0002

Article•10/01/2024

There must be no space character.

There must be no space character between a unary operator and its argument.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0003

Article•10/01/2024

There must be exactly one space character between the NOT operator and its argument.

There must be exactly one space character between the NOT operator and its argument.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0005

Article•10/01/2024

Only use BEGIN..END to enclose compound statements.

Only use BEGIN..END to enclose compound statements.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0008

Article•10/01/2024

Function calls should have parenthesis even if they do not have any parameters.

Use parenthesis in a function call even if the function does not have any parameters.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

```
７ Note
```
```
This rule doesn't give a warning on system methods referenced using property
syntax. For example, when accessing the system method RecordId from a Record
variable using RecId := MyRecord.RecordId instead of RecId :=
MyRecord.RecordId().
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0013

Article•10/01/2024

When BEGIN follows THEN, ELSE, DO, it should be on the same line, preceded by one
space character.

When BEGIN follows THEN, ELSE, DO, it should be on the same line, preceded by one
space character.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0018

Article•10/01/2024

The END, IF, REPEAT, UNTIL, FOR, WHILE, and CASE statement should always start a line.

The END, IF, REPEAT, UNTIL, FOR, WHILE, and CASE statement should always start a line.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0021

Article•10/01/2024

Variable declarations should be ordered by type.

Variable declarations should be ordered by type. In general, object and complex variable
types are listed first followed by simple variables.

Object and complex variable types must be listed first, and then simple variables. The
order is: Record, Report, Codeunit, XmlPort, Page, Query, Notification, BigText,
DateFormula, RecordId, RecordRef, FieldRef, and FilterPageBuilder. The rest of the
variables are not sorted.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0022

Article•10/01/2024

Substitute the IF THEN ELSE structure with a CASE.

An IF followed by two or more ELSE IF should be replaced with a CASE.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0040

Article•10/01/2024

Avoid using nested WITH statements.

It can be difficult to see what variable that a member variable or function refers to, when
nesting WITH statements of variables with different types.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0050

Article•10/01/2024

Permission set extensions should not include permissions for objects defined in another
application.

Permission set extensions should not include permissions for objects defined in another
application. This can pose a security risk by granting excessive privileges to users.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0051

Article•10/01/2024

Permission set extensions should not include permission sets defined in another
application.

Permission set extensions should not include permission sets from another application.
This can pose a security risk by granting excessive privileges to users.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0052

Article•10/01/2024

Permission set extensions should not include permission sets which include permissions
for objects defined in another application.

Permission set extensions should not include permission sets which include permissions
for objects defined in another application. This can pose a security risk by granting
excessive privileges to users.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0053

Article•10/01/2024

Permission set extensions should not include wildcard permissions.

Permission set extensions should not include wildcard permissions. Wildcard
permissions can pose a security risk by unintentionally granting excessive privileges to
users.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Info AA0072

Article•10/01/2024

The name of variables and parameters must be suffixed with the type or object name.

To improve readability the name of variables and parameters must be suffixed with the
type or object name.

For more information about best practices for AL, including using suffixes, see Best
Practices for AL.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

# CodeCop Warning AA0073

Article•10/01/2024

The name of temporary variable must be prefixed with Temp.

Only temporary variable names must be prefixed with Temp.

Temporary variables must be named with identifiers that abbreviate the word temporary,
such as temp. This improves readability of the code.

```
AL
```
```
AL
```
CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Reason for the rule

## Bad code example

```
JobWIPBuffer : Record "Job WIP Buffer" temporary;
```
## Good code example

```
TempJobWIPBuffer : Record "Job WIP Buffer" temporary;
```
## Related information

```
 Yes  No
```

Provide product feedback


# CodeCop Warning AA0074

Article•10/01/2024

TextConst and Label variable names should have an approved suffix.

TextConst and Label variable names should have a suffix (an approved three-letter suffix:
Msg, Tok, Err, Qst, Lbl, Txt) describing usage.

```
Three-letter suffix Meaning
Msg Message
```
```
Tok Token
Err Error
```
```
Qst StrMenu or Confirm
Lbl Label, Caption
```
```
Txt Text
```
```
AL
```
## Description

## Remarks

```
ﾉ Expand table
```
```
７ Note
```
```
The Tok suffix is generally used for short tokens such as "GET", "PUT", "HTTPS" etc.
Furthermore, the variable name should align with the label itself, for example,
GetTok, PutTok and HttpsTok. In general, these tokens should have the Locked =
true; set so that they're not translated.
```
## Example

```
// Label suffixed with Tok for Token
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get started with AL
Developing extensions

```
GetTok: Label 'GET', Locked = true;
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0087

Article•10/01/2024

Lowering permissions should only be used in tests

Do only lower permissions inside procedures of type test.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0100

Article•10/01/2024

Do not have identifiers with quotes in the name.

Do not have identifiers with quotes in the name.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0101

Article•10/01/2024

Use camel case property values in pages of type API.

For pages of the type API the value of properties APIPublisher, APIGroup, EntityName,
and EntitySetName value should be camel-cased to follow the Microsoft REST API
Guidelines.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0102

Article•10/01/2024

Use camel case name for field controls in pages of type API.

Field controls in pages of type API should have a camel case name in order to follow the
Microsoft REST API Guidelines.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0103

Article•10/01/2024

Use camel case property values in queries of type API.

For queries of the type API the value of properties APIPublisher, APIGroup, EntityName,
and EntitySetName value should be camel-cased to follow the Microsoft REST API
Guidelines.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0104

Article•10/01/2024

Use camel case name for column controls in queries of type API.

Column controls in queries of type API should have a camel case name in order to
follow the Microsoft REST API Guidelines.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Error AA0105

Article•10/01/2024

PagePart controls must not refer to parent pages.

PagePart controls must not refer to parent pages.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Error AA0106

Article•10/01/2024

A page of type API can only refer to the same subpage once.

A page of type API can only refer to the same subpage once.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0131

Article•10/01/2024

String parameters must match placeholders.

Remember to specify all string parameters to match placeholders.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0136

Article•10/01/2024

Do not write code that will never be hit.

Do not write code that will never be hit.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0137

Article•10/01/2024

Do not declare variables that are unused.

Do not declare variables that are unused.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0139

Article•10/01/2024

Do not assign a text to a target with smaller size.

Do not assign a text to a target with smaller size.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0150

Article•10/01/2024

Do not declare parameters by reference if their values are never changed.

Do not declare parameters by reference if their values are never changed.

Defining a parameter as passed by reference and not actually changing it may lead to an
unexpected variable value if the variable is later changed in the method. In addition,
other developers may think that the value is changed in the method, eventhough that is
not true.

The following example illustrates the developer's error - forgot to remove var property
of MyList in Method1, after redesigning Method2.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example 1

```
procedure Method1(var MyB: boolean)
begin
Method2(MyB);
end;
procedure Method2(MyC: boolean)
var
someVar: boolean;
begin
someVar := MyC;
end;
```
## Good code example 1

```
procedure Method1(MyB: boolean)
begin
Method2(MyB);
```

```
AL
```
```
AL
```
Variables of the following types are analyzed: Integer, BigInteger, Boolean, Byte, Char,

```
Code, Date, DateTime, Decimal, Time, and Text. Also lists and arrays of above types are
```
analyzed - these types should be changed with appropriate methods if they are passed
by reference.

Event subscribers, Integration Events, and ConfirmHanders are also not analyzed.
Parameters of the type List can be also changed following built-in methods: Add,

```
AddRange, Set, Insert, Remove, RemoveAt, RemoveRange, Reverse. Arrays additionally
```
changed by CompressArray and CopyArray. Also the Evaluate built-in method is

supported.

```
end;
procedure Method2(MyC: boolean)
var
someVar: boolean;
begin
someVar := MyC;
end;
```
### Bad code example 2

```
procedure Method1(var InvtValue: array[ 5 ] of Integer)
var
MyInt: Integer;
begin
MyInt := InvtValue[ 0 ];
end;
```
### Good code example 2

```
procedure Method1(InvtValue: array[ 5 ] of Integer)
var
MyInt: Integer;
begin
MyInt := InvtValue[ 0 ];
end;
```
### Remarks


#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0161

Article•10/01/2024

Only use AssertError in Test Codeunits.

Only use AssertError in Test Codeunits.

For more information, see AppSourceCop AS0058.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0175

Article•10/01/2024

Only find record if you need to use it.

Only find or get records if you are not using values.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0181

Article•10/01/2024

The FindSet() or Find() methods must be used only in connection with the Next()
method.

Avoid getting the dataset when an enumeration is not used, which will decrease
performance.

If you use FindSet() or Find() you must have a Next() method. Otherwise, you are

wasting CPU and bandwidth since multiple records are loaded but you only use one.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
codeunit 1 MyCodeunit
{
var
customer: Record Customer;
procedure Foo()
begin
if customer.FindFirst() then
repeat
...
until customer.Next() = 0 ;
end;
}
```
## Good code example

```
codeunit 1 MyCodeunit
{
var
customer : Record Customer;
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
procedure Foo()
begin
if customer.FindSet() then
repeat
...
until customer.Next() = 0 ;
end;
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0189

Article•10/01/2024

Only use a correct values of ApplicationArea.

ApplicationArea has invalid value.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0194

Article•10/01/2024

Only write actions that have an effect.

Remember to specify either the 'OnAction' trigger or the 'RunObject' property on an
action.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0198

Article•10/01/2024

Do not use identical names for local and global variables.

Do not use identical names for local and global variables.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0199

Article•10/01/2024

Use only a correct order for ApplicationArea.

The order of the specified ApplicationArea is incorrect.

The ApplicationArea names must be specified in the following order:

```
Invoicing, **Basic**, **Suite**, RelationshipMgmt, Jobs, FixedAssets, Location,
```
BasicHR, Assembly, ItemCharges, **Advanced**, Warehouse, Service, Manufacturing,

Planning, Dimensions, ItemTracking, Intercompany, SalesReturnOrder,

PurchReturnOrder, Prepayments, CostAccounting, SalesBudget, PurchaseBudget,

ItemBudget, SalesAnalysis, PurchaseAnalysis, InventoryAnalysis, XBRL, Reservation,
OrderPromising, ADCS, Comments, RecordLinks, Notes, VAT, SalesTax, ItemReferences,

BasicEU, BasicCA, BasicUS, BasicMX, BasicAU, BasicNZ, BasicAT, BasicCH, BasicDE,
BasicBE, BasicCZ, BasicDK, BasicES, BasicFI, BasicFR, BasicGB, BasicIS, BasicIT,

BasicNL, BasicNO, BasicRU, BasicSE

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0200

Article•10/01/2024

When ApplicationArea is set to 'All', no other values for ApplicationArea should be
specified.

'All' should always stand alone has incorrect order.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0201

Article•10/01/2024

When ApplicationArea is set to 'Basic', you must also specify 'Suite'.

When ApplicationArea is set to 'Basic', you must also specify 'Suite'.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0202

Article•10/01/2024

To avoid confusion, do not give local variables the same name as fields, methods, or
actions in the same scope.

To avoid confusion, do not give local variables the same name as fields, methods, or
actions in the same scope.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0203

Article•10/01/2024

To avoid confusion, do not give methods the same name as fields or actions in the same
scope.

To avoid confusion, do not give methods the same name as fields or actions in the same
scope.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0204

Article•10/01/2024

To avoid confusion, do not give global variables the same name as fields, methods, or
actions in the same scope.

To avoid confusion, do not give global variables the same name as fields, methods, or
actions in the same scope.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0205

Article•10/01/2024

Variables must be initialized before usage.

Always initialize a variable before usage. This can improve readability and make
debugging easier.

Using uninitialized variables may lead to strange behavior, the code may become harder
to debug and in some cases readability of the code can decrease.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example 1

```
var
x: Integer;
z: Integer;
procedure Proc1()
var
begin
Proc2(z);
x := z;
end;
```
```
procedure Proc2(z: Integer)
var
begin
z := 10 ;
end;
```
## Good code example 1

```
var
x: Integer;
z: Integer;
```

```
AL
```
```
AL
```
Variables of the following types are analyzed: Integer, BigInteger, Boolean, Byte, Char,
Code, Date, DateTime, Decimal, List, Record, and Time.

```
procedure Proc1()
var
begin
Proc2(z);
x := z;
end;
```
```
procedure Proc2(var z: Integer)
var
begin
z := 10 ;
end;
```
### Bad code example 2

```
procedure TestFunc()
var
a: Integer;
b: Integer;
begin
b := a + 1 ;
end;
```
### Good code example 2

```
procedure TestFunc()
var
a: Integer;
b: Integer;
begin
a := 0 ;
b := a + 1 ;
end;
```
### Remarks


#### Feedback

**Was this page helpful?**

Provide product feedback

Some variables need special initialization, for example, List is initialized using .Add(),

```
Record is initialized via .Init(), .Clear(), or assignment. Local record variables and
```
arrays are ignored. Global record variables can be initialized in other method.

Initialization is possible using evaluate, for, foreach statements. If a variable is passed in
a method through var, the rule considers it initialized in the method.

CodeCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# CodeCop Warning AA0206

Article•10/01/2024

The value assigned to a variable must be used.

The value assigned to a variable must be used, otherwise the variable is not necessary.

Unused variable can be confusing for the reader and can cost performance to the
system.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
procedure AddEntities@1(FilterStr@ 1000 : Text[ 250 ])
var
Vendor@ 1001 : Record Vendor;
Count@ 1002 : Integer;
begin
Count := 0 ;
Vendor.SETFILTER("No.",FilterStr);
if Vendor.FINDSET() then
repeat
"User ID" := USERID();
"Vendor No." := Vendor."No.";
If Vendor.Insert() THEN;
until Vendor.NEXT() = 0 ;
end;
```
## Good code example

```
procedure AddEntities@1(FilterStr@ 1000 : Text[ 250 ])
var
Vendor@ 1001 : Record Vendor;
begin
Vendor.SETFILTER("No.",FilterStr);
if Vendor.FINDSET() then
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Remove the variable or make use of it if not using it was a mistake.

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
repeat
"User ID" := USERID();
"Vendor No." := Vendor."No.";
if Vendor.INSERT() then;
until Vendor.NEXT() = 0 ;
end;
```
### Good and bad practices for fixing the rule

### Related information

```
 Yes  No
```

# CodeCop Warning AA0207

Article•10/01/2024

The EventSubscriber method must be local.

The EventSubscriber method must be local.

The method which is marked as an event subscriber must be local, because it must not
to used for external calls. Not marking the method as local might cause confusion.

```
AL
```
```
AL
```
Make the method local by adding the keyword local.

## Description

## Reason for the rule

## Bad code example

```
[EventSubscriber(ObjectType::Page, Page::"Customer Card",
'OnBeforeValidateEvent', 'Address', true, true)]
procedure CheckAddressLine(var Rec : Record Customer)
begin
...
end;
```
## Good code example

```
[EventSubscriber(ObjectType::Page, Page::"Customer Card",
'OnBeforeValidateEvent', 'Address', true, true)]
local procedure CheckAddressLine(var Rec : Record Customer)
begin
...
end;
```
## Good and bad practices for fixing the rule


#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Info AA0210

Article•10/01/2024

Avoid non-indexed fields into filtering.

Suboptimal index.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0211

Article•10/01/2024

Avoids a runtime error from using CalcFields on a field that is not a FlowField or a field
of type Blob.

CalcFields should only be used for FlowFields or Blob fields

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0213

Article•10/01/2024

Obsoleted object must have a state 'Pending' or 'Removed' and a justification specifying
why this field is being obsoleted.

Obsoleted object must have a state 'Pending' or 'Removed' and a justification specifying
why this field is being obsoleted.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0214

Article•10/01/2024

The local record should be modified before saving to the database.

The local record should be modified before saving to the database.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0215

Article•10/01/2024

Follow the style guide about the best practices for naming.

Follow the style guide about the best practices for naming.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0216

Article•10/01/2024

Use a text constant for passing user messages and errors without concatenations.

Use a text constant for passing user messages and errors without concatenations.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0217

Article•10/01/2024

Use a text constant or label for format string in StrSubstNo.

Use a text constant or label for format string in StrSubstNo.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0218

Article•10/01/2024

You must write a tooltip in the Tooltip property for all controls of type Action and Field
that exist on page objects.

You must write a tooltip in the Tooltip property for all controls of type Action and Field
that exist on page objects.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0219

Article•10/01/2024

The Tooltip property of Fields must start with 'Specifies'.

The Tooltip property of Fields must start with 'Specifies'.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0220

Article•10/01/2024

The value of the Tooltip property of Fields must be filled.

The value of the Tooltip property of Fields must be filled.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0221

Article•10/01/2024

You must specify a OptionCaption property for all fields which source expressions is not
a table field.

You must specify a OptionCaption property for all fields which source expressions is not
a table field.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0222

Article•10/01/2024

SIFT index should not be used on primary or unique key.

SIFT index should not be used on primary or unique key.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0223

Article•10/01/2024

The value of the OptionCaption property of Fields must be filled in.

The value of the OptionCaption property of Fields must be filled in.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0224

Article•10/01/2024

The count of option captions specified in the OptionCaption property is wrong.

The count of option captions specified in the OptionCaption property is wrong.

The number of option captions specified in the **OptionCaption** property must match the
number of option values available for a variable or a field on a page or report.

The following code sample will raise a warning because the number of option values
available for the page field "VAT Posting" is two, while only one option caption is

defined in the **OptionCaption** property.

```
AL
```
## Description

## Remarks

## Example

```
page 50100 MyPage
{
layout
{
area(Content)
{
field("VAT Posting"; postingOptions)
{
OptionCaption = 'Automatic VAT Entry';
}
}
}
var
postingOptions: Option "Automatic VAT Entry" , "Manual VAT Entry";
}
```
## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
OptionCaption Property
Get Started with AL
Developing Extensions

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0225

Article•10/01/2024

You must specify a caption in the Caption property for Fields that exist on page objects.

You must specify a caption in the Caption property for Fields that exist on page objects.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0226

Article•10/01/2024

The value of the Caption property of Fields must be filled in.

The value of the Caption property of Fields must be filled in.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0227

Article•10/01/2024

Optional return value should not be omitted in upgrade codeunits.

In upgrade codeunits always remember to specify optional return values on methods
that can cause run-time errors.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0228

Article•10/01/2024

The local method must be used; otherwise removed.

The local method must be used, otherwise the method is not necessary.

Unused methods can be confusing for the reader and can cost performance to the
system.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
codeunit 10 MyCodeunit
{
var
RenameErr: Label 'You cannot rename';
```
```
local procedure Method1()
begin
Message(RenameErr);
end;
procedure Method2()
begin
Error(RenameErr);
end;
}
```
## Good code example

```
codeunit 10 MyCodeunit
{
var
RenameErr: Label 'You cannot rename';
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Remove the unused local method from the code.

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
procedure Method2()
begin
Error(RenameErr);
end;
}
```
### Good and bad practices for fixing the rule

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0230

Article•10/01/2024

Version should not be specified for internal assemblies.

Version number should not be specified for internal assemblies to avoid errors during
upgrade procedures.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0231

Article•10/01/2024

StrSubstNo or string concatenation must not be used as a parameter in the Error
method.

The data classification context will be lost when using the StrSubstNo method or string
concatenation as a parameter in the Error method. Instead use the ability of the Error
method to insert values into the string with placeholders.

All error messages are logged into telemetry and we do not allow adding customer data
into telemetry. So, all errors that have a textconst as the first argument actually log the

```
textconst in telemetry, this greatly increases the ability to resolve errors found in
```
telemetry. If StrSubstNo or string concatenation is used as first argument the data
classification context is lost and no message text is logged in telemetry.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
var
ErrorMsg: Label 'Customer %1 has incorrect email', Comment = '%1 =
Customer No.';
```
```
local procedure MyProcedure()
begin
Error(StrSubstNo(ErrorMsg, Customer."No.");
end;
```
```
var
Text000Err: Label 'There are no planning lines to make orders for. ';
Text007Err: Label 'This template and worksheet are currently active. ';
local procedure MyProcedure()
begin
```

#### Feedback

**Was this page helpful?**

```
AL
```
```
AL
```
Use the ability of the Error method to insert values (expressions) into the string that has
a placeholder.

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
Error(Text000Err + Text007Err);
end;
```
### Good code example

```
var
ErrorMsg: Label 'Customer %1 has incorrect email', Comment = '%1 =
Customer No.';
local procedure MyProcedure()
begin
Error(ErrorMsg, Customer."No.");
end;
```
```
var
ErrorMsg: Label 'There are no planning lines to make orders for. This
template and worksheet are currently active. ';
local procedure MyProcedure()
begin
Error(ErrorMsg);
end;
```
### Good and bad practices for fixing the rule

### Related information

```
 Yes  No
```

Provide product feedback


# CodeCop Info AA0232

Article•10/01/2024

The FlowField of a table should be indexed.

You can potentially increase performance if fields that are used in FlowFields are added
to SumIndexedFields of the corresponding key.

When there are performance issues on List pages, the root cause is often that they
display FlowFields defined on top of tables that are inadequately indexed - these are
typically missing SIFT indices. As any FlowField potentially can be shown on a page,
make sure that they're all adequately indexed.

```
AL
```
## Description

## Reason for the rule

```
７ Note
```
```
Be aware that this rule can, in some cases, cause false warnings even though you
have addressed any performance issues by adding SIFT indices. The rule will be
fixed in a future release.
```
## Bad code example

```
table 18 Customer
{...
fields
{...
field( 97 ; "Debit Amount"; Decimal)
{
...
CalcFormula = Sum ("Detailed Cust. Ledg. Entry"."Debit Amount"
WHERE("Customer No." = FIELD("No."),
```
```
"Entry Type" = FILTER(<> Application),
"Initial Entry Global Dim. 1" = FIELD("Global Dimension 1 Filter"),
```
```
"Initial Entry Global Dim. 2" = FIELD("Global Dimension 2 Filter"),
```

```
AL
```
```
"Posting Date" = FIELD("Date Filter"),
```
```
"Currency Code" = FIELD("Currency Filter")));
FieldClass = FlowField;
...
}
...
}
keys { ... }
...
}
table 379 "Detailed Cust. Ledg. Entry"
{...
fields { ... }
keys
{
key(Key1; "Entry No.")
{
Clustered = true;
}
}
...
}
```
### Good code example

```
table 18 Customer
{...
fields
{...
field( 97 ; "Debit Amount"; Decimal)
{
...
CalcFormula = Sum ("Detailed Cust. Ledg. Entry"."Debit Amount"
WHERE("Customer No." = FIELD("No."),
"Entry Type" = FILTER(<> Application),
```
```
"Initial Entry Global Dim. 1" = FIELD("Global Dimension 1 Filter"),
"Initial Entry Global Dim. 2" = FIELD("Global Dimension 2 Filter"),
```
```
"Posting Date" = FIELD("Date Filter"),
"Currency Code" = FIELD("Currency Filter")));
FieldClass = FlowField;
...
}
...
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
}
keys { ... }
...
}
table 379 "Detailed Cust. Ledg. Entry"
{...
fields { ... }
keys
{
key(Key1; "Entry No.")
{
Clustered = true;
}
key(Key2; "Customer No.", "Entry Type", "Initial Entry Global Dim.
1", "Initial Entry Global Dim. 2", "Posting Date", "Currency Code")
{
SumIndexFields = "Debit Amount"
}
}
...
}
```
### Related information

```
 Yes  No
```

# CodeCop Warning AA0233

Article•10/01/2024

Use Get(), FindFirst() and FindLast() without Next() method.

Avoid enumeration of a dataset when the dataset is not filtered.

If you use FindFirst(), FindLast(), or Get(), then the database query will only fetch a

single record and must fetch again when you call Next(), which will lower performance.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
codeunit 1 MyCodeunit
{
var
customer: Record Customer;
```
```
procedure Foo()
begin
...
customer.FindFirst();
...
customer.Next();
...
end;
}
```
## Good code example

```
codeunit 1 MyCodeunit
{
var
customer : Record Customer;
procedure Foo()
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
begin
...
customer.FindFirst();
...
end;
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0234

Article•10/01/2024

You must write a tooltip in the Tooltip property for all fields on table objects.

You must write a tooltip in the Tooltip property for all fields on table objects. This helps
the users of your app to fill in the right value(s) in the field.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Info AA0235

Article•10/01/2024

When using 'OnInstallAppPerCompany' you should also add 'Company-
Initialize'::'OnCompanyInitialize' event subscriber.

When using trigger 'OnInstallAppPerCompany' in a codeunit with 'Subtype = Install' you
should also add a 'Company-Initialize'::'OnCompanyInitialize' event subscriber to ensure
that new companies also have the correct setup.

'OnInstallAppPerCompany' is only run on companies that exist when installing the
extension. Many extensions were missing a 'OnCompanyInitialize' subscription, so
companies that were created after the extension installation were missing setup that the
extension should do. For example, insertion of records in some tables was done only for
existing companies and not for new ones.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
codeunit 1160 "AP Install"
{
Subtype = Install;
trigger OnInstallAppPerCompany()
```
```
begin
...
end;
}
```
## Good code example

```
codeunit 1160 "AP Install"
{
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
Subtype = Install;
trigger OnInstallAppPerCompany()
```
```
begin
...
end;
```
```
[EventSubscriber(ObjectType::Codeunit, Codeunit::"Company - Initialize",
'OnCompanyInitialize', '', false, false)]
local procedure CompanyInitialize()
begin
...
end;
}
```
### Related information

```
 Yes  No
```

## Feedback

# CodeCop Warning AA0237

Article•10/01/2024

The name of non-temporary variables must not be prefixed with Temp.

Only temporary variable names must be prefixed with Temp.

Temporary variables must be named with identifiers that abbreviate the word temporary,
such as temp. This improves readability of the code. Therefore you should avoid using
temp for other purposes.

```
AL
```
```
AL
```
CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Reason for the rule

## Bad code example

```
TempJobWIPBuffer : Record "Job WIP Buffer";
```
## Good code example

```
CopyOfJobWIPBuffer : Record "Job WIP Buffer";
```
## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# CodeCop Warning AA0240

Article•10/01/2024

Email and Phone No must not be present in any part of the source code.

Email and Phone No must not be present in any part of the source code that might be
collected as telemetry data.

To prevent exposing personal data, make sure that Email or Phone No information is not
available in the source code because that might be collected as telemetry data.

```
AL
```
```
AL
```
## Description

## Reason for the rule

## Bad code example

```
table 18 Customer
{
...
fields
{
field( 1 ; Email; Text[ 50 ]){ CaptionML = ENU = 'john.smith@contoso.com';
}
}
...
}
```
## Good code example

```
table 18 Customer
{
...
fields
{
field( 1 ; Email; Text[ 50 ]){ CaptionML = ENU = 'Email'; }
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The following elements are checked in code:

```
Object names
Table captions
Table field names
Table field captions
Page captions
Page field names
Page field captions
Page field tooltips
Value of labels (in declaration)
Value of text constants
Translation files (tags <source>, <target>, <note>)
App manifest file (Name, Brief, Description, Publisher)
```
CodeCop Analyzer
Get Started with AL
Developing Extensions

```
...
}
```
### Remarks

### Related information

```
 Yes  No
```

# CodeCop Hidden AA0241

Article•10/01/2024

Use all lowercase letters for reserved language keywords.

Use all lowercase letters for reserved language keywords. This rule does not apply to
built-in methods and types; they must be written using Pascal case.

We recommend following these best practices when developing extensions in AL to
ensure consistency and discoverability on file, object, and method naming, as well as
better readability of written code.

Data types in variable and parameter declarations aren't included in this rule because
they're written using Pascal case.

```
AL
```
```
AL
```
## Description

## Remarks

## Bad code example

```
trigger OnValidate()
BEGIN
IF "Order Date" > "Starting Date" THEN
Error(Text007, FieldCaption("Order Date"), FieldCaption("Starting
Date"));
END;
```
```
VAR
Text007: Label '%1 cannot be greater than %2.';
```
## Good code example

```
trigger OnValidate()
begin
if "Order Date" > "Starting Date" then
error(Text007, FieldCaption("Order Date"), FieldCaption("Starting
Date"));
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Change _every reserved language keyword to use lowercase letters_. Use Pascal case for
data types in variable and parameter declarations.

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
end;
var
Text007: Label '%1 cannot be greater than %2.'; // Label variable
declaration in Pascal case
```
### Good and bad practices for fixing the rule

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0242

Article•10/01/2024

Limit JIT loads by selecting all fields for load.

When using Partial Records via SetLoadFields, you should only access fields that are
selected for load.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0243

Article•10/01/2024

Running an upgrade codeunit is not allowed.

Running codeunits of subtype upgrade will cause runtime error.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# CodeCop Warning AA0244

Article•10/01/2024

Do not use identical names for parameters and global variables.

Do not use identical names for parameters and global variables.

This CodeCop rule is similar to AA0198, but it applies to method parameters. The rule
warns when a method's parameters names collide with global variable names, but with
the following specifics for Event declaration.

AA0244 doesn't warn on Events with the exception of Integration Events that have
GlobalVarAccess set to true.

```
AL
```
```
AL
```
## Description

## Remarks

## No warning

```
codeunit 50100 MyCodeunit
{
// GlobalVarAccess = false hence we don't warn
[IntegrationEvent(true, false)]
local procedure MyNewEvent(EventParamA: Integer)
begin
end;
}
```
## Warning

```
codeunit 50100 MyCodeunit
{
// GlobalVarAccess = true hence we warn
[IntegrationEvent(true, true)]
local procedure MyNewEvent(EventParamA: Integer)
begin
```

#### Feedback

**Was this page helpful?**

Provide product feedback

CodeCop Analyzer
Getting Started with AL
Developing Extensions

```
end;
}
```
```
７ Note
```
```
Rule AA0244 warns on EventSubscribers and even if the subscribers don't have
control over the names of the parameters, they have control over the global
variables living in the Codeunit.
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0245

Article•10/01/2024

To avoid confusion, do not give parameters the same name as fields, methods, or
actions in the same scope.

To avoid confusion, do not give parameters the same name as fields, methods, or
actions in the same scope.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0246

Article•10/01/2024

Suppressing all diagnostics is not allowed.

Suppressing all diagnostics is not allowed. Specify the diagnostic(s) that you want to
suppress.

Enabling this rule allows to enforce that when suppressing diagnostics using
the #pragma warning disable, the code(s) of the diagnostics to suppress must be

specified instead of suppressing all analyzer diagnostics and compiler warnings.

CodeCop Analyzer
Getting Started with AL
Developing Extensions
Directives in AL

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Info AA0247

Article•10/01/2024

Use namespaces.

Use namespaces to organize your code and isolate it from changes.

CodeCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Hidden AA0248

Article•10/02/2024

Add 'this' qualification to improve readability.

Add 'this' qualification to improve readability.

This rule is hidden by default, which means that it appears as three dots in the editor,
but doesn't show up as a diagnostic in the **Problems** view in Visual Studio Code or in
any pipelines. The CodeCop rule identifies where you can take advantage of using the
this keyword. Use the workspace-wide code action to help you clean up your code.

Learn more about the this keyword in Use the this keyword for codeunit self-reference.

CodeCop Analyzer
Getting Started with AL
Developing Extensions
Use the this keyword for codeunit self-reference

## Description

## Remarks

## Related information

```
 Yes  No
```

# CodeCop Warning AA0448

Article•10/01/2024

You must use the FieldCaption method instead of the FieldName method and
TableCaption method instead of TableName method.

If you want to enable your application for multilanguage functionality, you must use the
FieldCaption and TableCaption methods instead of the FieldName and TableName
methods.

Use the FieldCaption(Record) method and the TableCaption(Record) method whenever
possible to return names of fields and tables as strings so correct translation will be
automatically used. As a result user can always recognize a term that indicates a field or
table name.

```
AL
```
## Description

## Reason for the rule

```
７ Note
```
```
The only exception to this rule is the Open(Dialog) method. In this method, you can
use the field name directly. Otherwise, it can be difficult to align correctly.
```
## Bad code example

```
trigger OnValidate()
begin
if "Order Date" > "Starting Date" then
Error(Text007, FieldName("Order Date"), FieldName("Starting Date"));
end;
var
Text007: Label '%1 cannot be greater than %2.';
```
## Good code example


#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
Change FieldName to FieldCaption or TableName to TableCaption.

The Open(Dialog) method is not checked and is an exception from this rule.

CodeCop Analyzer
Get Started with AL
Developing Extensions

```
trigger OnValidate()
begin
if "Order Date" > "Starting Date" then
Error(Text007, FieldCaption("Order Date"), FieldCaption("Starting
Date"));
end;
var
Text007: Label '%1 cannot be greater than %2.';
```
### Good and bad practices for fixing the rule

### Remarks

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CodeCop Warning AA0462

Article•10/01/2024

The CalcDate should only be used with DataFormula variables. Alternatively the string
should be enclosed using the <> symbols.

The CalcDate should only be used with DataFormula variables. Alternatively the string
should be enclosed using the < > symbols.

CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

# CodeCop Warning AA0470

Article•10/01/2024

Placeholders should have a comment explaining their content.

Provide an explanation that describes the content of each of the placeholders.

Documentation of placeholders is required in order to enable translators to properly
know the construct of the label to be translated.

```
AL
```
```
AL
```
CodeCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Reason for the rule

## Bad code example

```
MissingNodeErr: Label 'Cannot find an XML node that matches %1 or %2.';
```
## Good code example

```
MissingNodeErr: Label 'Cannot find an XML node that matches %1 or %2.',
Comment = '%1 = XML node name ; %2 = Parent XML node name';
```
## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0001

Article•10/01/2024

Tables and table extensions that have been published must not be deleted.

Tables and table extensions that have been published must not be deleted. This might
break the upgrade of existing installations and dependent extensions.

This rule validates tables independently of their Accessibility or ObsoleteState, because
tables are always used when synchronizing the schema defined in the extension to the
database.

This rule validates table extensions independently of the ObsoleteState of their target
tables. Table extensions extending a table, which is marked with obsolete state Removed
must be preserved, since they're still contributing to the database schema defined by
the extension.

Revert the changes done by adding back the tables and table extensions that have been
removed.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0002

Article•10/01/2024

Fields must not be deleted.

Fields must not be deleted. This might break the upgrade of existing installations and
dependent extensions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

```
７ Note
```
```
This rule validates all fields independently of their Accessibility or ObsoleteState,
because they are used when synchronizing the schema defined in the extension to
the database.
```
## Related information

```
 Yes  No
```

# AppSourceCop Error AS0003

Article•08/26/2024

The previous version of the extension could not be found.

The previous version of the extension, used as a baseline for detecting breaking
changes, could not be found in the package cache folder.

This rule validates that the version of the extension specified as a baseline for detecting
breaking changes can be found in the baseline package cache folder.

In order to set up AppSourceCop to detect breaking changes, the version of the
extension used as a baseline must be specified in the AppSourceCop.json file using the
version property. The version specified is the exact version against which the breaking

changes are validated. It is also possible to specify the name and the publisher of the

extension in the AppSourceCop.json file. The baselinePackageCachePath allows you to
specify the folder that will act as a cache for the baseline package and its dependencies
for the AppSourceCop analyzer.

If the baselinePackageCachePath is not specified, the baseline and its dependencies are

expected to be found in the dependency package cache path. The al.packageCachePath

setting allows you to specify the path to a folder that will act as the cache for the symbol
files used by your project. This is sufficient for most scenarios, but
baselinePackageCachePath provides a higher accuracy as it ensures that the previous

version of the extension will be loaded using the right version of its dependencies.

For example:

## Description

## Remarks

```
７ Note
```
```
The rule AS0091 verifies that the dependencies of the baseline can be found in the
baseline package cache folder.
```
## Setting up AppSourceCop to detect breaking changes


#### Feedback

**Was this page helpful?**

Provide product feedback

```
JSON
```
If you do not want to detect breaking changes in your extension, remove the property
version in the AppSourceCop.json file.

If you want to detect breaking changes, verify that the version specified in the
AppSourceCop.json file is correct and that the extension can be found in the baseline
package cache.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
{
"name": "ExtensionName",
"publisher": "ExtensionPublisher",
"version": "1.1.0.0",
"baselinePackageCachePath": "./.appSourceCopPackages"
}
```
```
７ Note
```
```
If you are using a workspace with multiple projects in Visual Studio Code, you must
set the baselinePackageCachePath property in the AppSourceCop.json file.
```
### How to fix this diagnostic?

### Related information

```
 Yes  No
```

# AppSourceCop Error AS0004

Article•10/01/2024

Fields must not change type, since dependent extensions may break

Fields must not change type.

The validation of the length of table fields was previously done with AS0004 and has
now been split into two different rules:

```
AS0080 - which validates against decreasing the length of fields
AS0086 - which validates against increasing the length of fields
```
To fix this diagnostic, you must obsolete the field by mark the field as Obsolete Pending
and then introduce a new field.

Version 1.0 of the app:

```
AL
```
## Description

```
７ Note
```
```
This rule validates all fields independently of their Accessibility or ObsoleteState,
because they are used when synchronizing the schema defined in the extension to
the database.
```
## Remarks

## How to fix this diagnostic?

## Example

```
table 50 MyTable
{
fields
{
field( 1 ; Identifier; Integer) { }
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the app:

```
AL
```
The data type of the field Identifier was changed from Integer to Text[30], which

isn't allowed and will trigger this rule.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
}
}
```
```
table 50 MyTable
{
fields
{
field( 1 ; Identifier; Text[ 30 ]) { }
}
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0005

Article•10/01/2024

Fields must not change name

Fields must not change name; their names are case-sensitive. This might break the
upgrade of existing installations and dependent extensions.

Version 1.0 of the app:

```
AL
```
Version 2.0 of the app:

```
AL
```
The field Identifier was renamed to Id, this is not allowed and will trigger this rule.

## Description

## Examples of non-valid name changes

## Example 1 - Rename field

```
table 50 MyTable
{
fields
{
field( 1 ; Identifier; Integer) { }
}
}
```
```
table 50 MyTable
{
fields
{
field( 1 ; Id; Integer) { }
}
}
```
## Example 2 - Change casing


Version 1.0 of the app:

```
AL
```
Version 2.0 of the app:

```
AL
```
The field Id had its casing changed to ID, this is not allowed and will trigger this rule.

Version 1.0 of the app:

```
AL
```
Version 2.0 of the app:

```
AL
```
```
table 50 MyTable
{
fields
{
field( 1 ; Id; Integer) { }
}
}
```
```
table 50 MyTable
{
fields
{
field( 1 ; ID; Integer) { }
}
}
```
###### Example 3 - Rename currently obsolete field

```
table 50 MyTable
{
fields
{
field( 10 ; "Cust. Rep."; Text[ 40 ])
{
ObsoleteState = Pending;
}
}
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The field Cust. Rep. was renamed to Alt. Name. It is not allowed to change the name
of a field if it is obsolete in both the previous and the new version, because the field is
still part of the extension's API.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
table 50 MyTable
{
fields
{
field( 10 ; "Alt. Name"; Text[ 40 ])
{
ObsoleteState = Pending;
}
}
}
```
```
７ Note
```
```
This rule validates all fields independently of their Accessibility or ObsoleteState,
because they are used when synchronizing the schema defined in the extension to
the database.
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0006

Article•10/01/2024

Tables that have been published must not change name.

Tables that have been published must not change name. This might break the upgrade
of existing installations and dependent extensions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

```
７ Note
```
```
This rule validates tables independently of their Accessibility or ObsoleteState,
because they are used when synchronizing the schema defined in the extension to
the database.
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0007

Article•10/01/2024

Objects that have been published must not change namespace.

Objects that have been published must not change namespace. This might break the
upgrade of existing installations and dependent extensions.

This rule does not exist anymore and has been replaced by:

```
AS0034 - For table property value changes
AS0036 - For field property value changes
AS0038 - For key property value changes
AS0039 - For table property removal
AS0041 - For field property removal
AS0042 - For key property removal
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0008

Article•10/01/2024

Defining reserved namespaces is not allowed.

The namespace must be different from System and Microsoft.

Using reserved namespaces like System or Microsoft can lead to conflicts and

unexpected behavior, as these namespaces are intended for the platform's internal
libraries and functionality. By enforcing this rule, AppSourceCop ensures that your code
remains isolated and doesn't interfere with the core system libraries, promoting better
maintainability and compatibility.

To resolve ths error, identify the namespace and change it to a unique name that
doesn't conflict with reserved namespaces.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0009

Article•08/26/2024

Key fields must not be changed

The list of fields for the primary key or for the clustered key must not be changed.

It is not allowed to change the list of fields for the primary key or for the clustered key
because this will break upgrade of existing installations. For more information on table
keys, see Table Keys.

In order to fix this diagnostic, you must revert the changes done in the current version
of your extension so that the list of fields for the primary key or the clustered key
matches the one defined for the key in your baseline extension.

For the following examples, version 1.0 of the extension defines the following table:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
This rule validates tables independently of their Accessibility or ObsoleteState,
because tables are always used when synchronizing the schema defined in the
extension to the database.
```
## How to fix this diagnostic?

## Code examples triggering the rule

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
```

These examples are demonstrating _breaking changes done on the primary key_. Similar
examples could be done on the clustered key:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the field MyDateField has been replaced by the field MyTextField in the

list of fields for the primary key. _This change is not allowed by the synchronization engine_.

Version 2.0 of the extension:

```
AL
```
```
}
keys
{
key(PK; MyIntegerField, MyDateField) { }
}
}
```
```
key(clusteredKey; MyIntegerField)
{
Clustered = true;
}
```
###### Example 1 - Modifying a field in the list

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
}
```
```
keys
{
key(PK; MyIntegerField, MyTextField) { }
}
}
```
###### Example 2 - Removing a field in the list


In version 2.0, the field MyDateField has been removed from the list of fields for the

primary key. _This change is not allowed by the synchronization engine_.

Version 2.0 of the extension:

```
AL
```
In the version 2.0, the field MyTextField has been added to the list of fields for the

primary key. _This change is not allowed by the synchronization engine_.

Any changes done on a key which is not the primary key or the clustered key are
allowed, see the following examples.

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
}
keys
{
key(PK; MyIntegerField) { }
}
}
```
###### Example 3 - Adding a field in the list

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
}
```
```
keys
{
key(PK; MyIntegerField, MyDateField, MyTextField) { }
}
}
```
### Code example not triggering the rule


Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the field MyDateField has been replaced by the field MyTextField in the
list of fields for the key SimpleKey. This change is allowed by the synchronization engine

because SimpleKey is not the primary key and is not the clustered key.

AppSourceCop Analyzer
Get Started with AL

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
}
```
```
keys
{
key(PK; MyIntegerField) { }
key(SimpleKey; MyDateField) { }
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyDateField; Date) { }
field( 3 ; MyTextField; Text[ 50 ]) { }
}
keys
{
key(PK; MyIntegerField) { }
key(SimpleKey; MyTextField) { }
}
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

Developing Extensions

```
 Yes  No
```

# AppSourceCop Error AS0010

Article•10/01/2024

Keys must not be deleted

The primary key must not be deleted because this will break upgrade of existing
installations.

It is not allowed to rename the primary key because this will break upgrade of existing
installations. Note that a primary key is always automatically generated for your table
even if you do not specify any keys in your AL code. Removing the primary key will then
be seen as a rename by the AppSourceCop analyzer. For more information on table
keys, see Table Keys.

In order to fix this diagnostic, you must rename the primary key or add it back so that it
matches its definition in your baseline extension.

Version 1.0 of the extension:

```
AL
```
## Description

```
７ Note
```
```
This rule validates tables independently of their Accessibility or ObsoleteState,
because tables are always used when synchronizing the schema defined in the
extension to the database.
```
## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - Renaming the primary key

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the key PK has been renamed to MyPK. _This change is not allowed by the_

_synchronization engine_.

Version 1.0 of the extension:

```
AL
```
```
}
keys
{
key(PK; MyIntegerField) { }
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
}
keys
{
key(MyPK; MyIntegerField) { }
}
}
```
```
７ Note
```
```
The validation of the primary key's name by the synchronization engine is case-
sensitive. Changing the casing of the primary key's name is then considered a
breaking change.
```
###### Example 2 - Explicitly adding a primary key

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
```

In version 1.0 of the extension, no primary key is explictly defined in AL code. By default,
the first field by ID will be used as primary key. The primary key is then similar to:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0 of the extension, a key named PK has been introduced and will act as the
primary key for the table. This is _not allowed_ because the primary key in version 1.0 was
named MyIntegerField.

Version 1.0 of the extension:

```
AL
```
```
}
}
```
```
key(MyIntegerField; MyIntegerField) { }
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
}
```
```
keys
{
key(PK; MyIntegerField) { }
}
}
```
```
７ Note
```
```
If the key introduced was named MyIntegerField, the change would be allowed
because it would match the default name given to the primary key in the baseline
version.
```
###### Example 3 - Removing the primary key


#### Feedback

Version 2.0 of the extension:

```
AL
```
In version 2.0 of the extension, no primary key is explictly defined in AL code. By default,
the first field by ID will be used as primary key. The primary key is then similar to:

```
AL
```
This change is _not allowed_ because the primary key was named PK in the baseline

extension while it is now named MyIntegerField.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
}
keys
{
key(PK; MyIntegerField) { }
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
}
}
```
```
key(MyIntegerField; MyIntegerField) { }
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0011

Article•08/26/2024

An affix is required

An affix is required.

In order to avoid name clashes for objects added by your extension and objects added
by other extensions, an affix must be prepended or appended to the name of all new
application objects, extension objects, and fields. For more information, see Benefits and
Guidelines for using a Prefix or Suffix.

The rule validates that at least one of the affixes specified in the mandatoryAffixes

property of the AppSourceCop.json file is used either at prefix or at suffix on identifier

names of new elements.

```
Setting Mandatory Value
mandatoryAffixes No Affixes that must be prepended or appended to the name of all
new application objects, extension objects, and fields.
```
The mandatoryAffixes property expects to receive an array of string as follows:

```
JSON
```
In order to preserve backward compatibility, the properties mandatoryPrefix and

```
mandatorySuffix are still supported by the AppSourceCop.
```
## Description

## Using the property mandatoryAffixes

```
ﾉ Expand table
```
```
{
"mandatoryAffixes": [ "Foo", "Bar" ]
}
```
## Using the properties mandatoryPrefix and

## mandatorySuffix


Both properties expect to receive a string as follows:

```
JSON
```
However, their meaning has been modified to be closer to the new mandatoryAffixes
property. The mandatory prefix and mandatory suffix properties are now both defining
an affix that can be used either as prefix or as suffix.

As a consequence, we encourage you to use the new property mandatoryAffixes that

offers more flexibility by allowing you to define more than two affixes, but also a more
meaningful name.

If you are not targeting the AppSource marketplace, you can suppress this rule using
rulesets.

For objects that are introduced with the current version of the extension, appending one
of the mandatory affixes to the object's name will fix the diagnostic. Renaming objects
which are not part of the baseline is allowed.

For objects which already exist in the version of the extension used as baseline, it is not
possible to rename them. It is therefore not possible to append one of the mandatory
affixes. Instead, the offending object should be deprecated using the ObsoleteState
property and a new object whose name has one of the mandatory affixes should be
introduced.

```
{
"mandatoryPrefix": "Prefix",
"mandatorySuffix": "Suffix"
}
```
### How to fix this diagnostic?

```
７ Note
```
```
If you are targeting the AppSource marketplace and do not have affixes registered,
follow the steps defined in Get Started with Building Apps.
```
###### For new objects

###### For existing objects


For instance, if the baseline of the extension contains a codeunit without affix:

```
AL
```
The extension should be modified into:

```
AL
```
```
７ Note
```
```
The lack of affixes for enum values defined in enum extensions is reported as a
warning with AS0098 if the enum value is already defined in your baseline
extension. If the enum value is not defined in your baseline extension, it is reported
as an error with AS0011. Make sure to specify your baseline extension in the
AppSourceCop.json file.
```
**Example - Adding an affix to an existing codeunit**

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```
```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use Foo_MyCodeunit instead.';
```
```
procedure MyProcedure()
var
c: Codeunit Foo_MyCodeunit;
begin
// Re-direct calls to not break the runtime behaviour of dependent
extensions.
c.MyProcedure();
end;
}
codeunit 50120 Foo_MyCodeunit
{
procedure MyProcedure()
begin
// Business logic.
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Once all dependent extensions have been updated to use the codeunit Foo_MyCodeunit

instead of MyCodeunit, the codeunit MyCodeunit can be removed.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
end;
}
```
```
７ Note
```
```
When new objects are added to this rule, the transition can be made gradually
because new objects are caught by the AS0011 rule, whereas the AS0098 rule
catches existing or modified objects. The warning with the same behavior is
described here: AS0098.
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0013

Article•08/26/2024

The field identifier must be within the allowed range

The field identifier must be within the allowed range and outside the range allocated to
per-tenant customizations.

In order to avoid ID clashes for objects added by your extension and objects added by
other extensions, you must respect the ID range specified in the app.json file of your
extension when declaring new AL objects. For more information about ID ranges in
Business Central, see Object Ranges.

The following illustrates an example of an app.json file specifying an ID range:

```
JSON
```
The rule AS0084 validates that the ID range has been specified in the app.json of the

extension.

## Description

## Remarks

```
{
"idRanges":
[
{
"from": 1000000 ,
"to": 1000100
}
]
}
```
```
７ Note
```
```
For table fields defined in table objects and enums defined in enum objects, it is
possible to use an ID within the range [0-49,999].
```
## Code examples


For the following examples, let's consider this app.json:

```
JSON
```
The following example triggers the rule because the ID of the codeunit MyCodeunit is

not defined within the ID range defined in the app.json file.

```
AL
```
The following example triggers the rule because the ID of the field MyField is not

defined within the ID range defined in the app.json file.

```
AL
```
```
{
"idRanges":
[
{
"from": 1000000 ,
"to": 1000100
}
]
}
```
###### Code example triggering the rule - Invalid Codeunit ID

```
codeunit 50100 MyCodeunit
{
// Business logic
}
```
###### Code example triggering the rule - Invalid Table

###### Extension Field ID

```
tableextension 1000000 MyTableExt extends MyTable
{
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
```
７ Note
```

If you are not targeting the AppSource marketplace, you can suppress this rule using
rulesets.

For objects that are introduced with the current version of the extension, changing the
ID of the object will fix the diagnostic. Changing the ID of objects which are not part of
the baseline is allowed.

For objects which already exist in the version of the extension used as baseline, it is not
possible to change their ID. Instead, the offending object should be deprecated using
the ObsoleteState property and a new object whose ID is within the range allocated for
the extension should be introduced.

As an example, let's consider an extension if the ID range assigned to the extension is
[1,000,000 - 1,000,100] and the extension defines:

```
AL
```
The extension should be modified into:

```
Fields defined in table objects are validated by AS0099.
```
### How to fix this diagnostic?

```
７ Note
```
```
If you are targeting the AppSource marketplace and do not have an ID range
assigned, follow the steps defined in Get Started with Building Apps.
```
###### For new objects

###### For existing objects

**Example - Modifying the ID of an existing codeunit**

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
Once all dependent extensions have been updated to use the codeunit MyNewCodeunit
instead of MyCodeunit, the codeunit MyCodeunit can be removed.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use MyNewCodeunit instead.';
```
```
procedure MyProcedure()
var
c: Codeunit MyNewCodeunit;
begin
// Re-direct calls to not break the runtime behaviour of dependent
extensions.
c.MyProcedure();
end;
}
codeunit 1000000 MyNewCodeunit
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0014

Article•10/01/2024

The project manifest must contain the allocated identifier range

The project manifest must contain the allocated identifier range.

This error occurs when the project manifest (app.json) doesn't include the allocated
identifier range for your extension. The identifier range is a set of unique IDs assigned to
your extension to avoid conflicts with other extensions.

To resolve this error, you must add the allocated identifier range to your project
manifest (app.json). Here are the steps:

1. Obtain the identifier range from Microsoft, if you don't already have one.
2. Open the app.json file in your project.
3. In the idRanges property, specify the allocated identifier range.

If your allocated identifier range is from 50000 to 59999, your app.json file should look
like this:

```
JSON
```
## Description

## Remarks

## How to fix this diagnostic?

## Example

```
{
"id": "your-app-id",
"name": "Your App Name",
"publisher": "Your Publisher Name",
"version": "1.0.0.0",
"idRanges": [
{
"from": 50000 ,
"to": 59999
}
],
```

#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
// Other properties
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0015

Article•10/01/2024

TranslationFile must be enabled.

The "TranslationFile" flag must be added to the "features" array in the app.json file.

To submit an app to AppSource, you must use XLIFF translation files. In the app.json file,
the setting "features": [ "TranslationFile" ] must be enabled. For more information,
see Working with Translation Files.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions
Working with Translation Files

## Description

## Remarks

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0016

Article•08/26/2024

Fields of field class 'Normal' must use the DataClassification property and its value
should be different from ToBeClassified

Fields of field class 'Normal' must use the DataClassification property and its value must
be different from ToBeClassified. FlowFields and FlowFilter fields are automatically set to
the SystemMetadata data classification.

For more information about data classification, see the documentation on the
DataClassification property and on Classifying Data in Dynamics 365.

In order to fix the diagnostics reported you must set the DataClassification property on
the table fields in your extension following the guidelines defined in Classifying Data in
Dynamics 365.

```
AL
```
## Description

## Remarks

```
７ Note
```
```
Tables and fields marked as Obsolete Removed are and not deleted from the
database. This is why they are also validated by this rule.
```
## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - No data classification specified

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ]) { }
```

The following example triggers the rule because the field MyField does not have any

DataClassification specified.

```
AL
```
The following example triggers the rule because the data classification for field MyField
still has to be classified.

```
AL
```
The following example does not trigger the rule because the data classification for field
MyField still has a valid data classification specified.

```
}
}
```
###### Example 2 - Data classification has to be classified

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ])
{
DataClassification = ToBeClassified;
}
}
}
```
### Code example not triggering the rule

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ])
{
DataClassification = CustomerContent;
}
}
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
 Yes  No
```

# AppSourceCop Error AS0018

Article•10/01/2024

A procedure belonging to the public API cannot be removed

A procedure that belongs to the public API cannot be removed, because it will break
dependent extensions calling this procedure.

Removing or renaming a procedure that belongs to the public API is not allowed,
because it will break dependent extensions which are referencing it. It is allowed to
remove or rename local or internal procedures.

Reverting the change will fix this diagnostic. If removing or renaming the procedure is
required, the recommended approach is to mark the procedure with the Obsolete
attribute. In a future version, once all dependent extensions have updated their code to
not reference the obsolete procedure, you can remove it or rename it.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
Internal procedures are also available for the modules specified in the
internalsVisibleTo property in your app.json file.
```
## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - Removing a public procedure

```
codeunit 50100 MyCodeunit
{
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the public procedure MyProcedure has been removed. If a dependent

extension referenced this procedure, this will lead to a compilation error similar to The
name 'MyProcedure' does not exist in the current context (AL0118).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
AL
```
```
procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
}
```
```
codeunit 50120 AnotherCodeunit
{
procedure AnotherMethod()
var
c: Codeunit MyCodeunit;
begin
c.MyProcedure();
end;
}
```
###### Example 2 - Renaming a public procedure

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
// Business logic
end;
}
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the public procedure MyProcedure has been renamed to

```
MyRenamedProcedure. If a dependent extension referenced this procedure, this will lead to
```
a compilation error similar to The name 'MyProcedure' does not exist in the current

context (AL0118).

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the local procedure MyProcedure has been removed. This is not a breaking

change because this procedure couldn't be referenced by other extensions.

```
codeunit 50100 MyCodeunit
{
procedure MyRenamedProcedure()
begin
// Business logic
end;
}
```
### Code examples not triggering the rule

###### Example 1 - Removing a local procedure

```
codeunit 50100 MyCodeunit
{
local procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the public procedure MyProcedure has been renamed to
MyRenamedProcedure. This is not a breaking change because this procedure couldn't be

referenced by other extensions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

###### Example 2 - Renaming an internal procedure

```
codeunit 50100 MyCodeunit
{
internal procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
internal procedure MyRenamedProcedure()
begin
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0019

Article•08/26/2024

Event attributes cannot be removed

Removing Event attributes such as IntegrationEvent or BusinessEvent is not allowed
because it will break dependent extensions that have subscribed to this event.

Removing the event attribute on Business and Integration type events is not allowed,
because it will break dependent extensions which are subscribing to them. It is allowed
to remove the InternalEvent attribute, as InternalEvents can only be subscribed to from
within the same module.

In the following examples, the version 1.0 of the extension defines a Business type event
whose accessibility is not public. This means that this event cannot be raised from other
extensions, but it can still be subscribed to from other extensions.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
Internal events are also available for the modules specified in the
internalsVisibleTo property in your app.json file.
```
## Code examples triggering the rule

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(i: Integer)
begin
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 2.0, the event attribute has been renamed. If a dependent extension
subscribed to this event, this will lead to a compilation error similar to Object member

'MyEvent' is not an event. (AL0281).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
codeunit 50100 MyCodeunit
{
local procedure MyEvent()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', false, false)]
local procedure MyProcedure(i: Integer)
begin
// Subscriber logic
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0020

Article•08/26/2024

The type of events cannot be changed.

The event attribute type cannot be changed because it might break dependent
extensions.

As part of your extension, you can publish events that will be available for other
extensions to subscribe to. In AL, you can define events of the following types:

```
BusinessEvent
IntegrationEvent
InternalEvent
```
This rule verifies that the conversion of an event from one version to another does not
potentially break dependent extensions.

It is not allowed to convert a business type event to an integration type event or to an
internal type event.

Business type events define a formal contract that carries an implicit promise not to
change in the future. Integration type events do not carry the same promise and can be
changed over time. It is then not allowed to convert a business type event to an
integration type event.

As a business type event defines an event that can be subscribed to by other dependent
extensions, it is not allowed to convert it to an internal event. This would break
dependent extensions which are subscribing to this event.

It is not allowed to convert an integration type event to an internal event.

## Description

## Remarks

## Converting business events

## Converting integration events


It is allowed to convert an integration type event to a business type event when the
following two conditions are met:

```
the integration event did not expose any global variables, and
the integration event does not stop exposing the sender to its subscribers (see
AS0021).
```
As an integration type event defines an event that can be subscribed to by other
dependent extensions, it is not allowed to convert it to an internal events. This would
break dependent extensions which are subscribing to this event.

Internal events can only be subscribed to from within the same module. It is then
allowed to turn them into business or integration type events.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
###### Converting internal events

### Examples of valid event type conversion

###### Example 1 - Converting an integration type event to a

###### business type event

```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(true)]
procedure MyEvent()
begin
end;
}
```

In the newer version of the extension, the sender remains exposed through the business
type event. The conversion is valid.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
The event MyEvent now becomes available for other extensions.

Version 1.0 of the extension:

```
AL
```
###### Example 2 - Converting an internal event to an

###### integration event

```
codeunit 50100 MyCodeunit
{
[InternalEvent(true)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, false)]
procedure MyEvent()
begin
end;
}
```
### Examples of nonvalid event type conversions

###### Example 1 - Conversion of a business type event to an

###### internal type event

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
procedure MyEvent()
```

Version 2.0 of the extension:

```
AL
```
In the newer version, the sender exposed by MyEvent is not accessible to subscribers

anymore. If a dependent extension relies on it, this will lead to a compilation error
similar to 'MyEvent' is inaccessible due to its protection level (AL0161).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
AL
```
```
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[InternalEvent(false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', true, true)]
local procedure MyProcedure()
begin
// Subscriber logic
end;
}
```
###### Example 2 - Conversion of an integration type event that

###### exposed variables to a business type event

```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, true)]
procedure MyEvent()
begin
```

Version 2.0 of the extension:

```
AL
```
In the newer version, the global variables exposed by MyEvent are not accessible to

subscribers anymore. If a dependent extension relies on global variables, this will lead to
a compilation error similar to The member referenced by event subscriber 'MyProcedure'

parameter 'myGlobalVariable' is not found (AL0282).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
end;
var
myGlobalVariable: Integer;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(true)]
procedure MyEvent()
begin
end;
```
```
var
myGlobalVariable: Integer;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', true, true)]
local procedure MyProcedure(myGlobalVariable: Integer)
begin
// Subscriber logic
end;
}
```
###### Example 3 - Conversion of an integration type event to a

###### business type event that stops exposing its sender


```
AL
```
Version 2.0 of the extension:

```
AL
```
In the newer version, the sender exposed by MyEvent is not accessible to subscribers

anymore. If a dependent extension relies on it, this will lead to a compilation error
similar to The member referenced by event subscriber 'MyProcedure' parameter
'sender' is not found (AL0282).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
AppSourceCop Analyzer
Get Started with AL

```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', true, true)]
local procedure MyProcedure(sender: Codeunit MyCodeunit)
begin
// Subscriber logic
end;
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

Developing Extensions

```
 Yes  No
```

# AppSourceCop Error AS0021

Article•10/01/2024

An argument in an event attribute cannot be changed to false.

An argument in an event attribute cannot be changed to false. This is not allowed
because it may break dependent extensions that have subscribed to this event.

This rule verifies that events that are available from other extensions such as Business
type events or Integration type events do not stop exposing their sender or their global
variables.

This does not apply to Internal type events as they are not exposed to dependent
extensions.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
## Description

## Remarks

## Code examples triggering the rule

## Example 1 - A business type event stops exposing its

## sender

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(true)]
procedure MyEvent()
begin
end;
}
```

In the newer version, the sender exposed by MyEvent is not accessible to subscribers
anymore. If a dependent extension relies on it, this will lead to a compilation error
similar to The member referenced by event subscriber 'MyProcedure' parameter
'sender' is not found (AL0282).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
AL
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', true, true)]
local procedure MyProcedure(sender: Codeunit MyCodeunit)
begin
// Subscriber logic
end;
}
```
###### Example 2 - An integration type event stops exposing

###### global variables

```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, true)]
procedure MyEvent()
begin
end;
var
myGlobalVariable: Integer;
}
```

Version 2.0 of the extension:

```
AL
```
In the newer version, the global variables exposed by MyEvent are not accessible to

subscribers anymore. If a dependent extension relies on global variables, this will lead to
a compilation error similar to The member referenced by event subscriber 'MyProcedure'

parameter 'myGlobalVariable' is not found (AL0282).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
AL
```
```
codeunit 50100 MyCodeunit
{
[IntegrationEvent(true, false)]
procedure MyEvent()
begin
end;
var
myGlobalVariable: Integer;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', true, true)]
local procedure MyProcedure(myGlobalVariable: Integer)
begin
// Subscriber logic
end;
}
```
### Code examples not triggering the rule

###### Example 1 - An event does not change over time

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
```

Version 2.0 of the extension:

```
AL
```
The event remains the same from one version to the other.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In the newer version of the extension, the sender becomes exposed through the
business type event.

```
procedure MyEvent()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
procedure MyEvent()
begin
end;
}
```
###### Example 2 - An event starts exposing its sender

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
procedure MyEvent()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(true)]
procedure MyEvent()
begin
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# AppSourceCop Error AS0022

Article•08/26/2024

An external scope cannot be removed

An external scope cannot be removed.

This rule verifies that procedures which were exposed to dependent extensions in the
previous version of the extension, remain exposed to other extensions.

The availability of a procedure is defined by:

```
the access modifier set on the object declaring the procedure
the access modifier set on the procedure
the Scope attribute that is added on the procedure
```
In the following examples, version 1.0 of the extension defines a procedure which is
public and available for Cloud development.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

## Description

## Remarks

## Code examples triggering the rule

```
codeunit 50100 MyCodeunit
{
[Scope('Cloud')]
procedure MyProcedure()
begin
end;
}
```
## Example 1 - Adding a local access modifier


```
AL
```
In version 2.0, the procedure is only accessible within its declaring codeunit. If a
dependent extension called this procedure, this will lead to a compilation error similar to
'MyProcedure()' is inaccessible due to its protection level. (AL0161).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure is only available for OnPrem development. If a dependent

extension uses the Cloud compilation target in the app.json and calls this procedure,

```
codeunit 50100 MyCodeunit
{
[Scope('Cloud')]
local procedure MyProcedure()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
procedure AnotherMethod()
var
c: Codeunit MyCodeunit;
begin
c.MyProcedure();
end;
}
```
###### Example 2 - Changing the Scope attribute from 'Cloud' to

###### 'OnPrem'

```
codeunit 50100 MyCodeunit
{
[Scope('OnPrem')]
procedure MyProcedure()
begin
end;
}
```

this will lead to a compilation error similar to The type or method 'MyProcedure' cannot

be used for 'Extension' development. (AL0296).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
In the following examples, version 1.0 of the extension defines a procedure which does
not have a return type.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
codeunit 50120 AnotherCodeunit
{
procedure AnotherMethod()
var
c: Codeunit MyCodeunit;
begin
c.MyProcedure();
end;
}
```
### Code examples not triggering the rule

```
codeunit 50100 MyCodeunit
{
[Scope('OnPrem')]
procedure MyOnPremProcedure()
begin
end;
```
```
local procedure MyLocalProcedure()
begin
end;
}
```
###### Example 1 - Removing a local access modifier


In version 2.0, the procedure MyLocalProcedure is now public and becomes available to
dependent extensions.

Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure MyOnPremProcedure becomes available for both OnPrem and

Cloud development. Any dependent extension can now call this procedure, regardless
of the compilation target specified in their app.json. The default Scope of a procedure is
Cloud. Removing the attribute is then also allowed.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
codeunit 50100 MyCodeunit
{
[Scope('OnPrem')]
procedure MyOnPremProcedure()
begin
end;
procedure MyLocalProcedure()
begin
end;
}
```
###### Example 2 - Changing the Scope attribute from 'OnPrem'

###### to 'Cloud'

```
codeunit 50100 MyCodeunit
{
[Scope('Cloud')]
procedure MyOnPremProcedure()
begin
end;
local procedure MyLocalProcedure()
begin
end;
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0023

Article•08/26/2024

A return type cannot be modified in external procedures

A return type cannot be modified in external procedures.

This rule validates that the return type of a public procedure has not been changed in a
way that would break the compilation of dependent extensions. It is not allowed to
change the return type of a public procedure that was published with a return type in a
previous version. Adding a return type is allowed by this rule, but is validated by
AS0102.

Reverting the change will fix this diagnostic. If changing the return type is required, the
recommended approach is to mark the procedure with the Obsolete attribute and
introduce a new one with the desired return type. In a future version, once all
dependent extensions have updated their code to not reference the obsolete procedure,
you can remove it.

In the following examples, version 1.0 of the extension defines a public procedure which
returns an Integer.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
This rule also covers the cases related to the TryFunction attribute which implicitly
defines a Boolean return type.
```
## How to fix this diagnostic?

## Code examples triggering the rule


Version 2.0 of the extension:

```
AL
```
In version 2.0, the return type of MyProcedure has changed from Integer to Boolean. If a

dependent extension used the return type of this procedure, this will lead to a
compilation error similar to Cannot implicitly convert type 'Boolean' to 'Integer'

(AL0122).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(): Integer
begin
exit( 5 );
end;
}
```
###### Example 1 - Changing the return type of a procedure

###### from Integer to Boolean

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(): Boolean
begin
exit(true);
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
procedure AnotherMethod()
var
c: Codeunit MyCodeunit;
myInt: Integer;
begin
myInt := c.MyProcedure();
end;
}
```
###### Example 2 - Removing the return type of a procedure


Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure does not return anything anymore. If a dependent
extension used the return type of this procedure, this will lead to a compilation error
similar to Cannot implicitly convert type 'None' to 'Integer' (AL0122).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
procedure AnotherMethod()
var
c: Codeunit MyCodeunit;
myInt: Integer;
begin
myInt := c.MyProcedure();
end;
}
```
###### Example 3 - Removing the return type of a procedure and

###### adding a TryFunction attribute

```
codeunit 50100 MyCodeunit
{
[TryFunction]
procedure MyProcedure()
begin
exit(true);
end;
}
```

In version 2.0, the procedure now returns a Boolean value because it is marked as a
TryFunction. This scenario would lead to the same compilation errors than mentioned in
Example 1 above.

In the following examples, the version 1.0 of the extension defines a procedure which
does not have a return type.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure MyProcedure is now returning a boolean. However, it does

not break the compilation of dependent extensions because they were not consuming
the return type of the procedure.

### Code examples not triggering the rule

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
end;
}
```
###### Example 1 - Adding a return type to a procedure

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(): Boolean
begin
exit(true);
end;
}
```
```
） Important
```
```
Adding a return type to a procedure is a runtime breaking changes. Dependent
extensions that are referencing the procedure must be recompiled in order to avoid
experiencing issues at runtime. For on-premises installations this can be done using
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure is now marked as a TryFunction. This means that this return
type has implicitly been changed to Boolean. Similarly, it is possible to add a TryFunction
attribute on a function that already returned a Boolean.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
Repair-NavApp. For SaaS, we do not allow adding return types, this is validated by
the rule AS0102.
```
###### Example 2 - Adding a TryFunction attribute to a

###### procedure

```
codeunit 50100 MyCodeunit
{
[TryFunction]
procedure MyProcedure()
begin
exit(true);
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0024

Article•10/01/2024

Parameters cannot be removed or added in external procedures

Parameters cannot be removed or added in external procedures, because it will break
dependent extensions.

It's not allowed to remove or add new parameters in public procedures as this will break
dependent extensions which are calling them.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
## Description

## Remarks

## Code examples triggering the rule

## Example 1 - Removing parameters

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
end;
}
```

In version 2.0, the parameter i of the procedure has been removed. If a dependent
extension calls this procedure, this will lead to a compilation error similar to No overload
for method 'MyProcedure' takes 1 argument. (AL0126).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, a new parameter j has been added to the procedure. If a dependent
extension calls this procedure, this will lead to a compilation error similar to There is no

argument given that corresponds to the required formal parameter 'j' of

'MyProcedure(Integer, Integer)' (AL0135).

```
codeunit 50120 AnotherCodeunit
{
procedure RaiseEvent()
begin
MyProcedure( 5 );
end;
}
```
###### Example 2 - Adding new parameters

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer; j: Integer)
begin
end;
}
```

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
In order to fix this diagnostic, the changes on the procedure signature must be reverted.
The procedure should be marked as obsolete, and a new procedure should be
introduced. The behavior of the obsoleted procedure should be preserved in order to
not break the runtime behavior of dependent extensions while they have not yet
uptaken the new procedure.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
codeunit 50120 AnotherCodeunit
{
procedure RaiseEvent()
begin
MyProcedure( 5 );
end;
}
```
### How to fix this diagnostic?

###### Example - Adding a parameter to a public procedure

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[Obsolete('Use MyProcedure(i: Integer;j: Integer) instead. This method
will be removed in version 3.0.', '2.0')]
procedure MyProcedure(i: Integer)
begin
end;
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Once dependent extensions have been updated to use the new procedure, the obsolete
procedure can be removed.

Version 3.0 of the extension:

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
procedure MyProcedure(i: Integer; j: Integer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer; j: Integer)
begin
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0025

Article•08/26/2024

Parameters cannot be modified, renamed, or removed from events.

Parameters cannot be modified, renamed, or removed from Business type and
Integration type events, because it will break dependent extensions.

Events defined in an extension can be referenced from dependent extensions, which can
raise them, subscribe to them, or both.

The rules AS0023, AS0024, and AS0026 validate against breaking changes in public
methods, which includes public events. They are then validating the scenarios around
events being raised from dependent extensions.

This rule validates that changes on the parameters of Business type and Integration
type do not break dependent extensions which subscribe to these events. As an event
subscriber can use the parameters passed by the event and references them by name,
removing parameters, modifying their type, and renaming them can break dependent
extensions.

In the following examples, the version 1.0 of the extension defines a Business type event
whose accessibility is not public. This means that this event can be subscribed to from
other extensions, but cannot be raised from other extensions.

Version 1.0 of the extension:

## Description

## Remarks

```
７ Note
```
```
Dependent extensions can subscribe to these events, even if the events are marked
with the local or internal access modifiers. The access modifier only limits the
ability to raise the event.
```
## Code examples triggering the rule


```
AL
```
Version 2.0 of the extension:

```
AL
```
In the version 2.0, the parameter i of the event has been removed. If a dependent
extension subscribed to this event and used i, this will lead to a compilation error

similar to The member referenced by event subscriber 'MyProcedure' parameter 'i' is

not found. (AL0282).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(i: Integer)
begin
end;
}
```
###### Example 1 - Removing parameters

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent()
begin
end;
}
```
```
codeunit 50120 AnotherCodeunit
{
[EventSubscriber(ObjectType::Codeunit, Codeunit::MyCodeunit, 'MyEvent',
'', false, false)]
local procedure MyProcedure(i: Integer)
begin
// Subscriber logic
end;
}
```
###### Example 2 - Modifying parameters


The dependent extension remains the same as in example 1.

Version 2.0 of the extension:

```
AL
```
In version 2.0, the type of the parameter i has changed from Integer to Boolean. If a

dependent extension subscribed to this event and used i, this will lead to a compilation
error similar to The type of the parameter 'i' on the event subscriber 'MyProcedure'

does not match the expected type 'Integer'. (AL0284).

The dependent extension remains the same as in example 1.

Version 2.0 of the extension:

```
AL
```
In version 2.0, the parameter i has been renamed to j. If a dependent extension

subscribed to this event and used i, this will lead to a compilation error similar to The
member referenced by event subscriber 'MyProcedure' parameter 'i' is not found.

(AL0282).

For local or internal events, it is allowed to add parameters to the event.

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(i: Boolean)
begin
end;
}
```
###### Example 3 - Renaming parameters

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(j: Integer)
begin
end;
}
```
### Code examples not triggering the rule


#### Feedback

**Was this page helpful?**

Provide product feedback

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the signature of the event has changed. However, it does not break
dependent extensions because event subscribers do not have to use all the parameters
defined in the event.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(i: Integer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
[BusinessEvent(false)]
local procedure MyEvent(i: Integer; j: Integer)
begin
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0026

Article•10/01/2024

The type and subtype of parameters cannot be modified in events and external
procedures

The type and subtype of parameters cannot be modified in events and external
procedures.

It's not allowed to change the type or subtype of parameters in public procedures as
this will break dependent extensions which are calling them.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
This rule allows to convert Option type parameters into Enum type parameters.
```
## Code examples triggering the rule

## Example 1 - Modifying parameters type

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Integer)
begin
end;
}
```

In version 2.0, the type of the parameter i has changed from Integer to Boolean. If a

dependent extension calls this method, this will lead to a compilation error similar to
Argument 1: cannot convert from 'Integer' to 'Boolean' (AL0133).

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the subtype of the parameter i has changed from a Customer record to a
Vendor record. If a dependent extension calls this method, this will lead to a compilation
error similar to Argument 1: cannot convert from 'Record Vendor' to 'Record Customer'

(AL0133).

AppSourceCop Analyzer
Get Started with AL

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Boolean)
begin
end;
}
```
###### Example 2 - Modifying parameters subtype

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Record Customer)
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(i: Record Vendor)
begin
end;
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0027

Article•10/01/2024

Modifying the array size of a parameter in events and external procedures is not allowed

Modifying the array size of a parameter in events and external procedures is not
allowed.

This error occurs when the array size of a parameter in events or external procedures is
modified. In AL, the array size of parameters in events and external procedures must
remain constant to ensure compatibility and stability.

To resolve this error, you must ensure that the array size of parameters in events and
external procedures isn't modified. Here are the steps:

1. Locate the event or external procedure in your code where the array size of a
    parameter is being modified.
2. Change the array size back to its original value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0028

Article•10/01/2024

Reducing the array size of a parameter in events and external procedures is not allowed

Reducing the array size of a parameter in events and external procedures is not allowed.

This error occurs when the array size of a parameter in events or external procedures is
reduced. In AL, the array size of parameters in events and external procedures must
remain constant to ensure compatibility and stability.

To resolve this error, you must ensure that the array size of parameters in events and
external procedures isn't modified. Here are the steps:

1. Locate the event or external procedure in your code where the array size of a
    parameter is being modified.
2. Change the array size back to its original value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0029

Article•09/27/2024

Pages and PageExtensions that have been published must not be deleted, since
dependent extensions may break

Pages and PageExtensions that have been published must not be deleted.

It's not allowed to remove pages which have been published unless they have been
marked as Obsolete. This will break dependent extensions which:

```
are referencing this page from code,
are extending the page using a page extension,
are customizing the page using page customizations.
```
In order to fix this diagnostic, the removal of the page extension must be reverted. The
page extension should also be marked as Obsolete instead, so that the page extension
can be removed in a future version.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
If a page coming from a dependency has been removed, AppSourceCop allows the
removal of page extensions extending it even if these page extensions have not
been previously marked as Obsolete.
```
## How to fix this diagnostic?

## Examples not triggering the rule

## Example 1 - Removing an obsolete page extension


Version 2.0 of the extension:

```
AL
```
Once dependent extensions have been updated to not reference the page extension
anymore, the page extension can be removed.

Version 3.0 of the extension:

```
AL
```
Version 1.0 of the extension:

```
AL
```
Let's consider that between version 1.0, the dependency defining "Customer Card" has
removed the page. Removing the page extension is then allowed.

Version 2.0 of the extension:

```
AL
```
```
pageextension 50100 MyCustomerCardExt extends "Customer Card"
{
// Some changes on the page.
}
```
```
pageextension 50100 MyCustomerCardExt extends "Customer Card"
{
ObsoleteState = Pending;
// Some changes on the page.
}
```
```
// Page extension has been removed
```
###### Example 2 - Removing a page extension targeting a

###### removed page

```
pageextension 50100 MyCustomerCardExt extends "Customer Card"
{
// Some changes on the page.
}
```

The following examples show some of the compilation errors that will be reported on
dependent extensions if a page is removed from one version to another.

Version 1.0 of the extension defines a page named MyPage. Version 2.0 does not define
this page anymore.

If a dependent extension references this page from code, when compiling against
version 2.0, this will lead to a compilation error similar to Page 'MyPage' is missing
(AL0185).

```
AL
```
If a dependent extension runs this page from code, when compiling against version 2.0,
this will lead to a compilation error similar to 'Page' does not contain a definition for

'MyPage' (AL0132).

```
AL
```
```
// Page extension has been removed
```
### Examples of errors for dependent extensions

###### Example 1 - Extensions referencing this page using a

###### variable

```
codeunit 50100 SomeCodeunit
{
procedure SomeProcedure()
var
p: Page MyPage;
begin
end;
}
```
###### Example 2 - Extensions running this page from code

```
codeunit 50100 SomeCodeunit
{
procedure SomeProcedure()
begin
Page.Run(Page::MyPage);
```

#### Feedback

If a dependent extension references this page from an action, when compiling against
version 2.0, this will lead to a compilation error similar to Page 'MyPage' is missing

(AL0185).

```
AL
```
If a dependent extension extends or customizes this page, when compiling against
version 2.0, this will lead to a compilation error similar to The target Page MyPage for
the extension object is not found (AL0247).

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
end;
}
```
###### Example 3 - Extensions running this page from an action

```
action(ActionName)
{
RunObject = page MyPage;
}
```
###### Example 4 - Extensions extending or customizing this

###### page

```
pageextension 50100 MyExtension extends MyPage
{
// Some additional changes on the page.
}
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0030

Article•08/26/2024

Pages that have been published must not be renamed.

Pages that have been published must not be renamed because it will break dependent
extensions.

It's not allowed to rename pages which have been published. This will break dependent
extensions which:

```
are referencing this page from code by name,
are extending the page by name using a page extension,
are customizing the page by name using page customizations.
```
It's allowed to rename page extensions, because page extensions can't be referenced by
name from a dependent extension.

Revert the change made on the page in order to keep the name defined previously.

If the rename was done in order to define the UI display of the page, consider using the
Caption property instead.

If the rename was done in order to comply with naming rules such as AS0011, consider
obsoleting the page and introducing a new one.

Renaming a page has the same consequences as removing it for dependent extensions
which are referencing it by name. You can then find examples of errors reported in
dependent extensions in rule AS0029.

## Description

## Remarks

## How to fix this diagnostic?

## Examples of errors for dependent extensions

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
 Yes  No
```

# AppSourceCop Error AS0031

Article•08/26/2024

Actions that have been published must not be deleted.

Actions that have been published must not be deleted, because it will break dependent
extensions.

Removing an action, which has been published isn't allowed because it will break
dependent extensions which are referencing or modifying it.

If the action was removed, revert the change by adding back the action and mark it as
Obsolete.

If the action was renamed in order to change its display string in the web client, consider
using the Caption property instead.

If the action was renamed in order to comply with naming rules such as AS0011,
consider obsoleting the action before introducing a new one in the next version of the
app.

## Description

## Remarks

```
７ Note
```
```
Renaming an action will also trigger this error. AppSourceCop will consider the
renamed action as a new action, unrelated to the one defined in the previous
version.
```
```
７ Note
```
```
From Business Central 2022 release wave 2 (version 21), removing the Promoted
property on an action is also considered a breaking change, since the AL compiler
automatically synthesizes an action reference for each promoted action.
```
## How to fix this diagnostic?


If the Promoted property was removed or set to false on an action, consider obsoleting
the action before modifying the promoted property in the next version of the app.

The following examples show some of the compilation errors that will be reported on
dependent extensions if an action is removed from one version to another.

Version 1.0 of the extension defines a page named MyPage that contains an action
named MyAction. Version 2.0 does not define this action anymore.

If a dependent extension modifies this action in a page extension or customization,
when compiling against version 2.0, this will lead to a compilation error similar to The

action 'MyAction' is not found in the target 'MyPage' (AL0271).

```
AL
```
If a dependent extension uses this action as an anchor for a change in a page extension
or customization, when compiling against version 2.0, this will lead to a compilation
error similar to The action 'MyAction' is not found in the target 'MyPage' (AL0271).

```
AL
```
### Examples of errors for dependent extensions

###### Example 1 - Extensions modify this action

```
pageextension 50100 SomePageExtension extends MyPage
{
actions
{
modify(MyAction)
{
Visible = true;
}
}
}
```
###### Example 2 - Extensions referencing this action as an

###### anchor for a change

```
pageextension 50100 SomePageExtension extends MyPage
{
actions
{
addafter(MyAction)
```

#### Feedback

**Was this page helpful?**

Provide product feedback

If a dependent extension is moving this action in a page extension or customization,
when compiling against version 2.0, this will lead to a compilation error similar to The

action 'MyAction' is not found in the target 'MyPage' (AL0271).

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
{
action(SomeNewAction)
{
}
}
}
}
```
###### Example 3 - Extensions moving this action

```
pageextension 50100 SomePageExtension extends MyPage
{
actions
{
movefirst(creation; MyAction)
}
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0032

Article•10/01/2024

Controls that have been published must not be deleted.

Controls that have been published must not be deleted, because it will break dependent
extensions.

Removing a control which has been published is not allowed because it will break
dependent extensions which are referencing or modifying it.

If the control was removed, revert the change by adding back the control and mark it as
Obsolete.

If the control was renamed in order to change its display string in the web client,
consider using the Caption property instead.

If the control was renamed in order to comply with naming rules such as AS0011,
consider obsoleting the control and introducing a new one.

The following examples show some of the compilation errors that will be reported on
dependent extensions if a control is removed from one version to another.

Version 1.0 of the extension defines a page named MyPage that contains a control
named MyControl. Version 2.0 does not define this control anymore.

## Description

## Remarks

```
７ Note
```
```
Renaming a control will also trigger this error. AppSourceCop will consider the
renamed control as a new control, unrelated to the one defined in the previous
version.
```
## How to fix this diagnostic?

## Examples of errors for dependent extensions


If a dependent extension modifies this control in a page extension or customization,
when compiling against version 2.0, this will lead to a compilation error similar to The

control 'MyControl' is not found in the target 'MyPage' (AL0270).

```
AL
```
If a dependent extension uses this control as an anchor for a change in a page extension
or customization, when compiling against version 2.0, this will lead to a compilation
error similar to The control 'MyControl' is not found in the target 'MyPage'

(AL0270).

```
AL
```
###### Example 1 - Extensions modify this control

```
pageextension 50100 SomePageExtension extends MyPage
{
layout
{
modify(MyControl)
{
Visible = true;
}
}
}
```
###### Example 2 - Extensions referencing this control as an

###### anchor for a change

```
pageextension 50100 SomePageExtension extends MyPage
{
layout
{
addafter(MyControl)
{
field(SomeNewControl; 15 )
{
}
}
}
}
```
###### Example 3 - Extensions moving this control


#### Feedback

**Was this page helpful?**

Provide product feedback

If a dependent extension is moving this control in a page extension or customization,
when compiling against version 2.0, this will lead to a compilation error similar to The
control 'MyControl' is not found in the target 'MyPage' (AL0270).

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
pageextension 50100 SomePageExtension extends MyPage
{
layout
{
movefirst(content; MyControl)
}
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0033

Article•08/26/2024

Views that have been published must not be deleted.

Views that have been published must not be deleted, because it will break dependent
extensions.

Removing a view which has been published is not allowed because it will break
dependent extensions which are referencing or modifying it.

If the view was removed, revert the change by adding back the view and mark it as
Obsolete.

If the view was renamed in order to change its display string in the web client, consider
using the Caption property instead.

If the view was renamed in order to comply with naming rules such as AS0011, consider
obsoleting the view and introducing a new one.

The following examples show some of the compilation errors that will be reported on
dependent extensions if a view is removed from one version to another.

Version 1.0 of the extension defines a list page named MyListPage that contains a view
named MyView. Version 2.0 does not define this view anymore.

## Description

## Remarks

```
７ Note
```
```
Renaming a view will also trigger this error. AppSourceCop will consider the
renamed view as a new view, unrelated to the one defined in the previous version.
```
## How to fix this diagnostic?

## Examples of errors for dependent extensions


If a dependent extension modifies this view in a page extension or customization, when
compiling against version 2.0, this will lead to a compilation error similar to The view

'MyView' is not found in the target 'MyListPage' (AL0533).

```
AL
```
If a dependent extension uses this view as an anchor for a change in a page extension or
customization, when compiling against version 2.0, this will lead to a compilation error
similar to The view 'MyView' is not found in the target 'MyListPage' (AL0533).

```
AL
```
If a dependent extension is moving this view in a page extension or customization, when
compiling against version 2.0, this will lead to a compilation error similar to The view

###### Example 1 - Extensions modify this view

```
pageextension 50100 SomePageExtension extends MyListPage
{
views
{
modify(MyView)
{
Visible = true;
}
}
}
```
###### Example 2 - Extensions referencing this view as an anchor

###### for a change

```
pageextension 50100 SomePageExtension extends MyListPage
{
views
{
addafter(MyView)
{
view(SomeNewView)
{
}
}
}
}
```
###### Example 3 - Extensions moving this view


#### Feedback

**Was this page helpful?**

Provide product feedback

'MyView' is not found in the target 'MyListPage' (AL0533).

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
pageextension 50100 SomePageExtension extends MyListPage
{
views
{
movefirst(MyView)
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0034

Article•10/01/2024

Unsupported table property change

Modifying table properties can lead to destructive changes that will break the upgrade
of existing installations and dependent extensions.

This error occurs when a table property is modified in a way that is not supported.
Modifying table properties can lead to destructive changes, which can break the
upgrade process for existing installations and dependent extensions.

To resolve this error, you need to avoid making unsupported changes to table
properties. Here are the steps:

1. Locate the table property in your code that is causing the error.
2. Change the property back to its original value or to a supported value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0035

Article•10/01/2024

Unsupported page property change

Modifying page properties can break the upgrade of existing installations and
dependent extensions.

This error occurs when a page property is modified in a way that isn't supported.
Modifying page properties can lead to destructive changes, which can break the
upgrade process for existing installations and dependent extensions.

To resolve this error, you need to avoid making unsupported changes to page
properties. Here are the steps:

1. Locate the page property in your code that is causing the error.
2. Change the property back to its original value or to a supported value.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0036

Article•10/01/2024

Unsupported table field property change

Modifying table field properties can lead to destructive changes that will break the
upgrade of existing installations and dependent extensions.

It's not allowed to change property values in a way that would prevent the schema
synchronization of the extension on existing installations, or that would break
dependent extensions.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
## Description

## Code examples triggering the rule

## Example 1 - Changing Enabled from true to false

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Enabled = true; // This is also the default value.
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Enabled = false;
```

In version 2.0, the field is not enabled anymore. Disabled fields are not created in the
database during schema synchronization. Disabling a field is then similar to removing
the field and is then a destructive change.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the field became a FlowField. As FlowFields are not physical fields that are
stored in the database, they are not created during schema synchronization. Changing a
Normal field to FlowField is a then destructive change.

```
}
}
}
```
###### Example 2 - Changing FieldClass from Normal to

###### FlowField

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
FieldClass = Normal; // This is also the default value.
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
FieldClass = FlowField;
}
}
}
```

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the field MyField is now only accessible within MyTable and cannot be
used from other extension. If a dependent extension references this field, this will lead
to a compilation error similar to 'MyField' is inaccessible due to its protection
level (AL0161).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
###### Example 3 - Changing the Access property to make a field

###### less accessible

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Access = Public; // This is also the default value.
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Access = Local;
}
}
}
```
```
codeunit 50120 AnotherCodeunit
{
trigger OnRun()
var
r: Record MyTable;
```

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the field is now enabled. Disabled fields are not created in the database
during schema synchronization. For the schema synchronization, enabling a field is then
similar to creating a new field and is then not a destructive change.

```
begin
r.MyField := 1 ;
end;
}
```
### Code examples not triggering the rule

###### Example 1 - Setting Enabled from false to true

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Enabled = false;
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Enabled = true; // This is also the default value.
}
}
}
```
###### Example 2 - Changing FieldClass from FlowField to

###### Normal


Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the FlowField became a Normal field. As FlowFields are not physical fields
that are stored in the database, they are not created during schema synchronization. For
the schema synchronization, changing a flow field to a normal field is similar to creating
a new field and is then not a destructive change.

Version 1.0 of the extension:

```
AL
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
FieldClass = FlowField;
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
FieldClass = Normal; // This is also the default value.
}
}
}
```
###### Example 3 - Changing the Access property to make a field

###### more accessible

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 1.0, MyField was accessible to table extensions extending MyTable. In version

2.0, it is now accessible to other extensions both in and outside of table extensions
extending MyTable. This is not a breaking change.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

```
Access = Protected;
}
}
}
```
```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer)
{
Access = Public;
}
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0038

Article•10/01/2024

Unsupported table key property change

Modifying table key properties can lead to destructive changes that will break the
upgrade of existing installations and dependent extensions.

This error occurs when a table key property is modified in a way that isn't supported.
Modifying table key properties can lead to destructive changes, which can break the
upgrade process for existing installations and dependent extensions.

To resolve this error, you need to avoid making unsupported changes to table key
properties. Here are the steps:

1. Locate the table key property in your code that is causing the error.
2. Change the property back to its original value or to a supported value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0039

Article•10/01/2024

Removing properties that cause destructive changes is not allowed

Destructive table properties that have been published must not be removed.

This error occurs when an attempt is made to remove table properties that have already
been published and are considered destructive. Destructive changes can lead to data
loss, corruption, or other issues that can break the upgrade process for existing
installations and dependent extensions.

To resolve this error, you need to avoid removing published table properties that are
considered destructive. Here are the steps:

1. Locate the table property in your code that is being removed.
2. Restore the property to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0040

Article•10/01/2024

Removing properties that cause destructive changes is not allowed

Destructive page properties that have been published must not be removed.

This error occurs when an attempt is made to remove page properties that have already
been published and are considered destructive. Destructive changes can lead to data
loss, corruption, or other issues that can break the upgrade process for existing
installations and dependent extensions.

To resolve this error, you need to avoid removing published page properties that are
considered destructive. Here are the steps:

1. Locate the page property in your code that is being removed.
2. Restore the property to its original state.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0041

Article•10/01/2024

Table field property changes that cause destructive changes must not be removed

Removing table field properties can lead to destructive changes that will break the
upgrade of existing installations and dependent extensions.

This error occurs when an attempt is made to remove table field properties that have
already been published and are considered destructive. Destructive changes can lead to
data loss, corruption, or other issues that can break the upgrade process for existing
installations and dependent extensions.

To resolve this error, you need to avoid removing published table field properties that
are considered destructive. Here are the steps:

1. Locate the table field property in your code that is being removed.
2. Restore the property to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0042

Article•10/01/2024

Table key property changes that cause destructive changes must not be removed

Table key property changes that cause destructive changes must not be removed.

This error occurs when an attempt is made to remove table key properties that have
already been published and are considered destructive. Destructive changes can lead to
data loss, corruption, or other issues that can break the upgrade process for existing
installations and dependent extensions.

To resolve this error, you need to avoid removing published table key properties that are
considered destructive. Here are the steps:

1. Locate the table key property in your code that is being removed.
2. Restore the property to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0043

Article•10/01/2024

The clustered key must not be deleted

The clustered key must not be deleted.

It's not allowed to rename or remove the clustered key in a table. For more information
on table keys, see Table Keys.

In order to fix this diagnostic, you must rename the clustered key or add it back so that
it matches its definition in your baseline extension.

Version 1.0 of the extension:

```
AL
```
## Description

```
７ Note
```
```
This rule validates tables independently of their Accessibility or ObsoleteState,
because tables are always used when synchronizing the schema defined in the
extension to the database.
```
## How to fix this diagnostic?

## Code examples triggering the rule

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyTextField; Text[ 50 ]) { }
}
keys
{
key(PK; MyIntegerField) { }
key(ClusteredKey; MyTextField)
```

Version 2.0 of the extension:

```
AL
```
In version 2.0 of the extension, the clustered key ClusteredKey has been removed. _This_

_change is not allowed by the synchronization engine_.

```
AL
```
```
{
Clustered = true;
}
}
}
```
###### Example 1 - Removing the clustered key

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyTextField; Text[ 50 ]) { }
}
keys
{
key(PK; MyIntegerField) { }
}
}
```
###### Example 2 - Renaming the clustered key

```
table 50100 MyTable
{
fields
{
field( 1 ; MyIntegerField; Integer) { }
field( 2 ; MyTextField; Text[ 50 ]) { }
}
```
```
keys
{
key(PK; MyIntegerField) { }
```
```
key(NewClusteredKey; MyTextField)
{
Clustered = true;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

In version 2.0 of the extension, the clustered key has been renamed from ClusteredKey

to NewClusteredKey. This change is detected as a removal of ClusteredKey and _is not_

_allowed by the synchronization engine_.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0044

Article•10/01/2024

Property changes that cause destructive changes are not allowed

Destructive field properties that have been published must not be modified.

This error occurs when an attempt is made to modify field properties that have already
been published and are considered destructive. Destructive changes can lead to data
loss, corruption, or other issues that can break the upgrade process for existing
installations and dependent extensions.

To resolve this error, you need to avoid modifying published field properties that are
considered destructive. Here are the steps:

1. Locate the field property in your code that is being removed.
2. Restore the property to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0047

Article•10/01/2024

The extension name is too long.

The extension name length must not exceed the limit of 200 characters.

This rule verifies that the extension name specified in the app.json does not exceed 50
characters.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0048

Article•10/01/2024

The publisher name is too long.

The extension publisher length must not exceed the limit of 50 characters.

This rule verifies that the extension publisher specified in the app.json does not exceed
50 characters.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0049

Article•10/01/2024

The access modifier of an application object cannot be changed to a value that provides
less access.

The access modifier of an application object cannot be changed to a value that provides
less access because it will break dependent extensions. You can only change the
accessibility to provide more access.

This error occurs when the access modifier of an application object is changed to a more
restrictive value. Changing the access level to provide less access can break dependent
extensions that rely on the original access level. Access modifiers define the visibility and
accessibility of application objects, such as tables, pages, and codeunits.

To resolve this error, you need to avoid changing the access modifier to a more
restrictive value. Instead, you can only change the access level to provide more access.
Here are the steps:

1. Locate the application object in your code where the access modifier has been
    changed.
2. Restore the access modifier to its original value or change it to a less restrictive
    value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0050

Article•08/26/2024

The extensibility of an application object cannot be removed

The extensibility of an application object cannot be removed.

This rule verifies that an object that was extensible in the previous version of the
extension, remains extensible in the current version of the extension.

The extensibility of an object is defined by the Extensible property.

Version 1.0 of the extension defines a page which is extensible:

```
AL
```
Version 2.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
The default property value for the Extensible property differs depending on the
object type. For more information, see Extensible property.
```
## Code examples triggering the rule

## Example 1 - Changing the Extensible property value from

## true to false

```
page 50100 MyPage
{
Extensible = true;
}
```

In version 2.0, the page is not extensible anymore. If a dependent extension extends this
page, this will lead to a compilation error similar to The object Page 'MyPage' is not
extensible. AL(0564).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
The version 1.0 of the extension defines an enum which is extensible:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the enum is not extensible anymore, because the default extensibility for
enums is false. If a dependent extension extends this enum, this will lead to a
compilation error similar to The object Enum 'MyEnum' is not extensible. AL(0564).

```
page 50100 MyPage
{
Extensible = false;
}
```
```
pageextension 50120 SomePageExtension extends MyPage
{
}
```
###### Example 2 - Removing the extensible property on an

###### Enum

```
enum 50100 MyEnum
{
Extensible = true;
```
```
value( 50100 ; MyEnumValue) { }
}
```
```
enum 50100 MyEnum
{
value( 50100 ; MyEnumValue) { }
}
```

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
In the following examples, the version 1.0 of the extension defines an enum which is not
extensible.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the enum MyEnum is now extensible by dependent extensions.

```
enumextension 50120 SomeEnumExtension extends MyEnum
{
}
```
### Code examples not triggering the rule

```
enum 50100 MyEnum
{
Extensible = false;
value( 50100 ; MyEnumValue) { }
}
```
###### Example 1 - Changing the Extensible property value from

###### false to true

```
enum 50100 MyEnum
{
Extensible = true;
value( 50100 ; MyEnumValue) { }
}
```
###### Example 2 - Removing the Extensible property on a non

###### extensible Enum


#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 2.0, the enum MyEnum remains not extensible, because the default property
value is also false for enums.

For object for which the default property value for the Extensible property is true,
removing the property makes the object extensible.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
enum 50100 MyEnum
{
value( 50100 ; MyEnumValue) { }
}
```
###### Example 3 - Removing the Extensible property on object

###### types which are extensible by default

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0051

Article•10/01/2024

Manifest property is required for AppSource submission

The manifest property must be specified and contain a meaningful value. The value of
the property might be displayed to users in the AppSource marketplace.

The list of properties, which must be specified in the manifest of extensions targeting
the AppSource marketplace can be found in App.json file.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0052

Article•10/01/2024

The property 'url' must be set to a valid URL

The property 'url' must be set to a valid URL.

To resolve this error, you need to ensure that the 'url' property is set to a valid URL. Here
are the steps:

1. Locate the 'url' property in your code that is causing the error.
2. Ensure that the URL is correctly formatted and points to a valid web address.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0053

Article•10/01/2024

The compilation target of an application must be a value that is allowed in a multi-
tenant SaaS environment

The compilation target of an application must be a value that is allowed in a multi-
tenant SaaS environment.

This rule validates that the manifest of your extension (app.json) specifies a compilation
target that is allowed in a multi-tenant SaaS environment. For more information, see
JSON files and Compilation Scope Overview.

You must set the value of target property in the manifest of your extension (app.json)

to Cloud.

The following manifest specifies OnPrem as compilation target and is then not allowed in

a multi-tenant SaaS environment.

```
JSON
```
## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
{
"appId": "<some-guid>",
"name": "MyApp",
"publisher": "MyPublisher",
"version": "1.0.0.0",
"target": "OnPrem"
}
```
## Code example not triggering the rule


#### Feedback

**Was this page helpful?**

Provide product feedback

The following manifest specifies Cloud as compilation target and is allowed in a multi-

tenant SaaS environment.

```
JSON
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
{
"appId": "<some-guid>",
"name": "MyApp",
"publisher": "MyPublisher",
"version": "1.0.0.0",
"target": "Cloud"
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0054

Article•10/01/2024

The AppSourceCop configuration must specify the set of affixes used by the application

The AppSourceCop configuration must specify one of the following properties:
'mandatorySuffix', 'mandatoryPrefix', or 'mandatoryAffixes'. The use of these affixes is
validated by the AppSourceCop analyzer and helps prevent conflicts between different
AppSource applications.

In the AppSourceCop.json configuration file, use the mandatorySuffix, mandatoryPrefix,
or mandatoryAffixes to specify which affixes apply for this particular extension. For

example:

```
JSON
```
For more information, see AppSourceCop Rule AS0011.

The use of affixes is required for extensions submitted to the AppSource marketplace,
see Technical Validation Checklist.

In order to register your affixes, see Benefits and Guidelines for using a Prefix or Suffix.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions Benefits and Guidelines for using a Prefix or Suffix

## Description

## Remarks

```
{
"mandatoryAffixes": [ "Foo", "Bar" ]
}
```
## Registering your affixes for AppSource

## submissions

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Hidden AS0055

Article•10/01/2024

The AppSourceCop configuration must specify the list of countries/regions targeted by
the application

The AppSourceCop configuration must specify the list of countries/regions targeted by
the application.

In the AppSourceCop.json file specify the setting as shown in the example below:

```
JSON
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

```
"supportedCountries": ["DE", "AT"];
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0056

Article•10/01/2024

The country/region codes specified in the 'supportedCountries' property must be valid
ISO 3166-1 alpha-2 codes

The country/region codes specified in the 'supportedCountries' property must be valid
ISO 3166-1 alpha-2 codes. Each code must correspond to a country/region for which
the product allows AppSource submissions. See Country/Regional availability and
Supported Translations for more information.

To resolve this warning, you need to ensure that all country/region codes specified in
the 'supportedCountries' property are valid ISO 3166-1 alpha-2 codes. Here are the
steps:

1. Locate the 'supportedCountries' property in your app.json file.
2. Check each code to ensure it's a valid ISO 3166-1 alpha-2 code. You can refer to
    the ISO 3166-1 alpha-2 code list for reference.
3. Replace any non-valid codes with valid ones.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

# AppSourceCop Hidden AS0057

Article•10/01/2024

Translations must be provided for all the locales in which the application will be available

Translations must be provided for all the locales in which the application will be
available.

This error occurs when translations aren't provided for all the locales in which the
application is intended to be available. Each locale represents a specific language and
region, and providing translations ensures that users in different locales can use the
application in their preferred language.

To resolve this error, you need to provide translations for all the locales in which the
application will be available. Here are the steps:

1. Determine all the locales in which your application will be available.
2. Create translation files for each locale, ensuring that all user-facing text is
    translated.
3. Add the translation files to your project and reference them appropriately.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0058

Article•10/01/2024

Only use AssertError in Test Codeunits

Only use AssertError in Test Codeunits.

AssertError must be used only in test codeunits, because it creates its own transaction
scope. This can lead to unexpected behaviors when used in production code.

For more information about the usage of AssertError, see:

```
AssertError statements
Testing the application overview
TransactionModel property
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions
CodeCop AA0161

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0059

Article•10/01/2024

Reserved database tables are read-only in a multi-tenant environment

Application database tables and reserved application tables should be used only as
temporary tables in a multi-tenant environment. Writing to these tables can lead to
runtime errors or unexpected behavior.

This error occurs when an attempt is made to write to reserved database tables in a
multi-tenant environment. In such environments, application database tables and
reserved application tables should only be used as temporary tables. Writing to these
tables can lead to runtime errors or unexpected behavior.

To resolve this error, you need to ensure that reserved database tables are only used as
temporary tables in a multi-tenant environment. Here are the steps:

1. Locate the code where a write operation is being attempted on a reserved
    database table.
2. Change the code to use the table as a temporary table instead of writing directly
    to it.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0060

Article•10/01/2024

Unsafe methods cannot be invoked in an AppSource application

The method cannot be invoked in an AppSource application because it can lead to
runtime errors or undefined behavior.

This error occurs when an unsafe method is invoked in an AppSource application.
Unsafe methods are those that can lead to runtime errors or undefined behavior,
making them unsuitable for use in applications published on AppSource.

To resolve this error, you need to avoid invoking unsafe methods in your AppSource
application. Here are the steps:

1. Locate the code where an unsafe method is being invoked.
2. Find a safe alternative to the unsafe method and replace it in your code.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0061

Article•10/01/2024

Procedures must not subscribe to CompanyOpen events

Procedures must not subscribe to CompanyOpen events because it can increase the
login time for Dynamics 365 Business Central.

To improve the login time for Dynamics 365 Business Central, extensions should no
longer use the **OnBeforeCompanyOpen** and **OnAfterCompanyOpen** events. For more
information, see Replacing OnBeforeCompanyOpen and OnAfterCompanyOpen.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0062

Article•08/26/2024

Page controls and actions must use the ApplicationArea property

Page controls and actions must use the ApplicationArea property to be visible to users.
From runtime 11.0, you can specify on the application object level the ApplicationArea
to use as default for all its controls and actions.

Application areas represent a feature in the system that offers developers,
administrators, and users the ability to define differentiated user experiences. They are
mapped to controls to show or hide them on page objects to enable more or fewer
business scenarios. Controls or actions without application area are not displayed in
SaaS.

This rule validates that the ApplicationArea property is set on actions and controls. For

more information, see ApplicationArea Property.

You must add the ApplicationArea property.

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
page 50100 MyPage
{
layout
{
area(Content)
{
field(MyField; 150 ) { }
}
}
actions
{
```

The field MyField and the action MyAction are not valid because they do not have the

```
ApplicationArea property set.
```
```
AL
```
The field MyField and the action MyAction are valid because they have the
ApplicationArea property set.

```
area(Processing)
{
action(MyAction) { }
}
}
}
```
### Code example not triggering the rule

###### ApplicationArea property set on each members

```
page 50100 MyPage
{
layout
{
area(Content)
{
field(MyField; 150 )
{
ApplicationArea = All;
}
}
}
actions
{
area(Processing)
{
action(MyAction)
{
ApplicationArea = All;
}
}
}
}
```
###### ApplicationArea property set on the object


From runtime version 10.0, field, part, and action controls without ApplicationArea
inherit the ApplicationArea defined on the page/report level.

The following code will then not trigger this analyzer diagnostic.

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions
ApplicationArea Property

```
page 50100 MyPage
{
ApplicationArea = All;
layout
{
area(Content)
{
field(MyField; 150 )
{
// ApplicationArea is inherited from the page.
}
}
}
actions
{
area(Processing)
{
action(MyAction)
{
// ApplicationArea is inherited from the page.
}
}
}
}
```
```
７ Note
```
```
This inheritance does not apply to members defined in extension objects like page
extensions or report extensions.
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0063

Article•10/01/2024

Removing a var modifier in events is not allowed

Removing a var modifier on a parameter in an event is not allowed as it will break
dependent extensions subscribing to it.

This error occurs when the var modifier is removed from a parameter in an event. The
var modifier indicates that the parameter is passed by reference, allowing the event

subscriber to modify the parameter's value. Removing the var modifier changes the
parameter to be passed by value, which can break dependent extensions that rely on
the original behavior.

To resolve this error, you need to ensure that the var modifier isn't removed from

parameters in events. Here are the steps:

1. Locate the event in your code where the var modifier has been removed from a
    parameter.
2. Restore the var modifier to the parameter.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0064

Article•10/01/2024

Interface implementations that have been published must not be deleted.

An interface implementation that has been published must not be deleted, because
dependent extensions may break.

This error occurs when an attempt is made to delete an interface implementation that
has already been published. Deleting a published interface implementation can break
dependent extensions that rely on it, leading to runtime errors and loss of functionality.

To resolve this error, you need to ensure that published interface implementations aren't
deleted. Here are the steps:

1. Locate the interface implementation in your code that is being deleted.
2. Restore the interface implementation to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0065

Article•10/01/2024

Interfaces that have been published must not be deleted.

An interface that has been published must not be deleted, because dependent
extensions may break.

This error occurs when an attempt is made to delete an interface that has already been
published. Deleting a published interface can break dependent extensions that rely on it,
leading to runtime errors and loss of functionality.

To resolve this error, you need to ensure that published interface aren't deleted. Here
are the steps:

1. Locate the interface in your code that is being deleted.
2. Restore the interface to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0066

Article•10/01/2024

A new method to an interface that has been published must not be added.

A new method to an interface that has been published must not be added, because
dependent extensions may break

This error occurs when an attempt is made to add a new method to an interface that has
already been published. Adding a new method to a published interface can break
dependent extensions that rely on it, leading to runtime errors and loss of functionality.

To resolve this error, you need to ensure that new methods aren't added to a published
interface. Here are the steps:

1. Locate the method on the interface in your code that is being added.
2. Restore the interface to its original state.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0067

Article•10/01/2024

Adding an interface to an enum that has been published must have a default
implementation.

Adding an interface to an enum that has been published must have a default
implementation, because dependent enum extensions don't implement the new
interface and may break.

When an extensible enum implements an interface, the AL compiler validates that all of
its enum values implement this interface. This applies to enum values defined in the
enum itself and to the enums defined in enum extensions. When an extensible enum
that was part of the previous version of this extension implements a new interface, a
default interface implementation must be specified using the Default implementation
property because dependent extensions extending this enum won't be implementing
the interface explicitly.

Add the Default implementation to the enum that implements a new interface.

In the following examples, the version 1.0 of the extension defines an extensible enum
which doesn't implement any interface.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
enum 50100 MyEnum
{
Extensible = true;
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the enum implements an interface. If a dependent extension extends this
enum, this will lead to a compilation error similar to Value 'MyExtValue' does not

implement interface 'MyInterface' and there is no default implementation for the

mentioned interface. (AL0596).

For example, the following extension compiles when depending on version 1.0, but fails
to compile with version 2.0:

```
AL
```
Version 1.0 of the extension:

```
value( 0 ; MyValue) { }
}
```
```
interface MyInterface
{
procedure MyProcedure()
}
codeunit 50100 MyImplementation implements MyInterface
{
procedure MyProcedure()
begin
end;
}
enum 50100 MyEnum implements MyInterface
{
Extensible = true;
value( 0 ; MyValue)
{
Implementation = MyInterface = MyImplementation;
}
}
```
```
enumextension 50100 MyEnumExtension extends MyEnum
{
value( 50100 ; MyExtValue) { }
}
```
### Code example not triggering the rule


#### Feedback

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the enum specifies a default implementation, which will prevent
compilation errors for dependent extensions extending this enum.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
enum 50100 MyEnum
{
Extensible = true;
```
```
value( 0 ; MyValue) { }
}
```
```
interface MyInterface
{
procedure MyProcedure()
}
codeunit 50100 MyImplementation implements MyInterface
{
procedure MyProcedure()
begin
end;
}
enum 50100 MyEnum implements MyInterface
{
Extensible = true;
DefaultImplementation = MyInterface = MyImplementation;
value( 0 ; MyValue)
{
Implementation = MyInterface = MyImplementation;
}
}
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0068

Article•10/01/2024

Changing a table extension's target is not allowed.

Changing the target of a table extension that has been published is not allowed,
because this might break the upgrade of existing installations and dependent
extensions.

This error occurs when an attempt is made to change the target table of a table
extension that has already been published. The target table of a table extension defines,
which table the extension is augmenting. Changing this target can disrupt the upgrade
process for existing installations and break dependent extensions that rely on the
original target table.

To resolve this error, you need to avoid changing the target table of a published table
extension. Here are the steps:

1. Locate the table extension in your code where the target table has been changed.
2. Restore the target table to its original value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0069

Article•10/01/2024

An enum field replacing an option field should have at least the same number of
members.

An enum field replacing an option field should have at least the same number of values
as the number of options members defined on the field in the previous version of the
extension. Having fewer members might break the upgrade of existing installations and
dependent extensions.

This error ensures that when you replace an option field with an enum field, the new
enum field must include all the values that were present in the original option field. This
is crucial because reducing the number of values can lead to data loss or corruption
during the upgrade process. Additionally, dependent extensions that rely on the original
option values may fail if those values are not present in the new enum field.

To resolve this error, follow these steps:

1. Locate the enum field in your code that is replacing an option field.
2. Ensure that the enum field has at least the same number of members as the option
    field it replaces.
3. If the enum field has fewer members, add the missing members to match the
    original option field.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0070

Article•10/01/2024

An enum field replacing an option field should preserve the member names.

An enum field replacing an option field should preserve the member names. Renaming
members might break the upgrade of existing installations and dependent extensions.

This error ensures that when you replace an option field with an enum field, the new
enum field must include all the values that were present in the original option field. This
is crucial because reducing the number of values can lead to data loss or corruption
during the upgrade process. Additionally, dependent extensions that rely on the original
option values may fail if those values are not present in the new enum field.

To resolve this error, follow these steps:

1. Locate the enum field in your code that is replacing an option field.
2. Ensure that the enum field has at least the same number of members as the option
    field it replaces.
3. If the enum field has fewer members, add the missing members to match the
    original option field.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0071

Article•10/01/2024

An enum field replacing an option field should preserve the member ordinal values.

An enum field replacing an option field should preserve the member ordinal values.
Modifying the member ordinal values might break the upgrade of existing installations
and dependent extensions.

This error ensures that when you replace an option field with an enum field, the ordinal
values (the numerical values assigned to each member) of the enum members must
match those of the original option members. Changing these ordinal values can lead to
data inconsistencies and corruption during the upgrade process. Additionally,
dependent extensions that rely on specific ordinal values may fail if those values are
altered in the new enum field.

To resolve this error, follow these steps:

1. Locate the enum field in your code that is replacing an option field.
2. Ensure that the ordinal values of the enum members match those of the original
    option members.
3. If the ordinal values don't match, adjust the enum members to preserve the
    original ordinal values.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

） **Note:** The author created this article with assistance from AI. Learn more

## Description

## Remarks

## How to fix this diagnostic?

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Hidden AS0072

Article•08/26/2024

The ObsoleteTag property and the Tag in the Obsolete attribute must be set to the next
release version.

The ObsoleteTag property and the Tag in the Obsolete attribute must be set to the next
release version (Major.Minor). This rule is only relevant if the Major.Minor format is set.

This rule verifies that the version specified as obsolete tag for objects whose obsolete
state (not obsolete, obsolete pending, or obsolete removed) is updated with the current
version is matching the version specified in the obsoleteTagVersion property of the

AppSourceCop.json.

Obsolete objects which have the same obsolete state as in the baseline are not validated
by this rule, but are validated by AS0074.

The version specified as obsoleteTagVersion can be the same as the current

Major.Minor version specified in the version of your app.json, but it does not have to.

The diagnostics for rule AS0072 are hidden by default, so you have to use a ruleset in
order to surface them.

For example, the following ruleset turns the diagnostic for rule AS0072 into an error.

## Description

## Remarks

```
７ Note
```
```
This rule is only enabled when using the default obsoleteTagPattern in the
AppSourceCop.json.
```
## Setting up AppSourceCop to validate the

## Obsolete tag

## Enabling the rule using a ruleset


```
JSON
```
```
JSON
```
In order to enable the validation, you must specify the obsoleteTagVersion in the

AppSourceCop.json, without specifying the obsoleteTagPattern property so that the

default pattern is used.

```
JSON
```
In order to fix this diagnostic, make sure that all objects which are changing obsolete
state in comparison to the baseline have an obsolete tag whose value is the one
specified in the obsoleteTagVersion of the AppSourceCop.json.

```
{
"name": "My custom ruleset",
"rules": [
{
"id": "AS0072",
"action": "Error",
"justification": "Validating that obsolete tags have the right
version is important"
}
]
}
```
```
{
"al.ruleSetPath": "custom.ruleset.json"
}
```
```
７ Note
```
```
In order to fully validate obsolete properties and attributes, it is recommended to
enable the rules AS0072 , AS0073 , AS0074 , AS0075 , and AS0076.
```
###### Setting up the AppSourceCop.json

```
{
"obsoleteTagVersion": "2.0"
}
```
### How to fix this diagnostic?


In the following example, the AppSourceCop is run against a baseline which has version
1.0 and expects the obsolete tag version for objects changing obsolete states to be 2.0.

```
JSON
```
Version of the extension used as baseline:

```
AL
```
Current version of the extension:

```
AL
```
### Example of code triggering this rule

```
{
"version": "1.0",
"obsoleteTagVersion": "2.0"
}
```
###### Newly obsoleted object specifying a version different

###### than the obsolete tag version

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Integer) { }
}
```
```
procedure MyProcedure()
begin
end;
}
```
```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '2.1';
fields
{
field( 50100 ; MyField; Integer) { }
}
[Obsolete('Use function Y instead', '3.0')]
procedure MyProcedure()
```

In the current version of the extension, the table and the procedure are marked as
obsolete pending. However, the obsolete tag values specified in the AL code are higher
than the one specified in the AppSourceCop.json. The rule AS0072 will be triggered.

Version of the extension used as baseline:

```
AL
```
Current version of the extension:

```
AL
```
In the current version of the extension, the table's obsolete state is changed from
obsolete pending to obsolete removed, which means that only upgrade code is now
able to reference it. However, the obsolete tag value specified in the AL code has not

```
begin
end;
}
```
###### Preserving the obsolete tag for an object that changes

###### obsolete state

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '1.0';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
```
table 50100 MyTable
{
ObsoleteState = Removed;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '1.0';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```

been updated and is now lower than the one specified in the AppSourceCop.json. The
rule AS0072 will be triggered.

In the following example, the AppSourceCop is run against a baseline which has version
1.0 and expects the obsolete tag version for objects changing obsolete states to be 2.0.

```
JSON
```
Version of the extension used as baseline:

```
AL
```
Current version of the extension:

```
AL
```
### Example of code not triggering this rule

```
{
"version": "1.0",
"obsoleteTagVersion": "2.0"
}
```
###### Specifying a version equal to the target obsolete tag

###### version

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '2.0';
```
```
[Obsolete('Use function Y instead', '2.0')]
procedure MyProcedure()
begin
end;
}
```

The codeunit MyCodeunit is marked as obsolete with the current version of the
extension. As the specified obsolete tags are matching the obsoleteTagVersion, no
diagnostics are reported.

Version of the extension used as baseline:

```
AL
```
Current version of the extension:

```
AL
```
In the current version of the extension, the table's obsolete state is changed from
obsolete pending to obsolete removed, which means that only upgrade code is now
able to reference it. The obsolete tag value specified in the AL code has also been
updated to the current obsoleteTagVersion in the AppSourceCop.json. The rule AS0072

will not be triggered.

###### Updating the obsolete tag for an obsolete object that

###### does changes obsolete state

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '1.0';
```
```
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
```
table 50100 MyTable
{
ObsoleteState = Removed;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '2.0';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
The codeunit MyCodeunit is marked as obsolete pending in the baseline and remains
obsolete in the current version. The obsolete tag is then not validated by rule AS0072,
but is validated by AS0074. Note that this example does not trigger any diagnostics
from the AppSourceCop for obsolete tags.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

###### Preserving the obsolete tag for an object that does not

###### change obsolete state

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '1.0';
```
```
[Obsolete('Use function Y instead', '1.0')]
procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '1.0';
[Obsolete('Use function Y instead', '1.0')]
procedure MyProcedure()
begin
end;
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Hidden AS0073

Article•10/01/2024

Obsolete Tag must be set.

Obsolete Tag must be set.

When an object, element, variable or procedure is marked as obsolete, you should also
specify an obsolete tag. The obsolete tag can be used to provide information, such as
the timeline of the deprecation, to developers that are referencing it. The obsolete tag
appears in the message of the diagnostics AL0432 and AL0433 reported by the AL
compiler when referencing obsolete elements.

The format of the Obsolete tag is not validated by the AL compiler. However, you can
specify an expected format to be validated by the AppSourceCop. For more information,
see AS0076.

The diagnostics for rule AS0073 are hidden by default, so you first have to use a ruleset
in order to surface them.

For example, the following ruleset turns the diagnostic for rule AS0073 into an error.

```
JSON
```
## Description

## Remarks

## Setting up AppSourceCop to validate the

## Obsolete Tag

```
{
"name": "My custom ruleset",
"rules": [
{
"id": "AS0073",
"action": "Error",
"justification": "Validating that obsolete tags are specified is
important"
}
```

```
JSON
```
When the property Obsolete State is used to mark an object as Obsolete Pending or

```
Obsolete Removed, you need to also specify the property Obsolete Tag.
```
When the attribute Obsolete is used, you need to specify the obsolete tag attribute
parameter.

```
AL
```
```
]
}
```
```
{
"al.ruleSetPath": "custom.ruleset.json"
}
```
```
７ Note
```
```
In order to fully validate obsolete properties and attributes, it is recommended to
enable the rules AS0072 , AS0073 , AS0074 , AS0075 , and AS0076.
```
### How to fix this diagnostic?

### Code examples triggering the rule

###### Example 1 - Table marked as Obsolete Pending

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'This table has been deprecated for reason X. Use table
Y instead.';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
###### Example 2 - Procedure marked as Obsolete


```
AL
```
```
AL
```
```
AL
```
```
codeunit 50100 MyCodeunit
{
[Obsolete('This procedure is being deprecated for reason X. Use
procedure Y instead.')]
procedure MyProcedure()
begin
// Business logic.
end;
}
```
### Code examples not triggering the rule

###### Example 1 - Table marked as Obsolete Pending

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'This table is being deprecated for reason X. Use table
Y instead.';
ObsoleteTag = 'This table is being deprecated with the newest build of
the product.';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
###### Example 2 - Procedure marked as Obsolete

```
codeunit 50100 MyCodeunit
{
[Obsolete('This procedure is being deprecated for reason X. Use
procedure Y instead.', 'This table is being deprecated with the newest build
of the product.')]
procedure MyProcedure()
begin
// Business logic.
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# AppSourceCop Hidden AS0074

Article•08/26/2024

The Obsolete Tag must be the same across branches.

The Obsolete Tag must be the same across branches. This rule is only relevant only if the
Major.Minor format is set.

This rule verifies that the version specified as obsolete tag for objects that do not
change obsolete state (not obsolete, obsolete pending, or obsolete removed) with the
current version has not changed.

Obsolete objects which do not have the same state as in the baseline are not validated
by this rule, but are validated by AS0072.

The version specified as obsoleteTagVersion can be the same as the current

Major.Minor version specified in the version of your app.json, but it does not have to.

The diagnostics for rule AS0074 are hidden by default, so you first have to use a ruleset
in order to surface them.

For example, the following ruleset turns the diagnostic for rule AS0074 into an error.

```
JSON
```
## Description

## Remarks

```
７ Note
```
```
This rule is only enabled when using the default obsoleteTagPattern in the
AppSourceCop.json.
```
## Setting up AppSourceCop to validate the

## Obsolete tag

## Enabling the rule using a ruleset


```
JSON
```
In order to enable the validation, you must specify the obsoleteTagVersion in the

AppSourceCop.json, but not specify the obsoleteTagPattern property to use the default

pattern.

```
JSON
```
In order to fix this diagnostic, make sure that all objects which did not change obsolete
state in comparison to the baseline have an obsolete tag whose value is the one
specified in the obsoleteTagVersion of the AppSourceCop.json.

```
{
"name": "My custom ruleset",
"rules": [
{
"id": "AS0074",
"action": "Error",
"justification": "Validating that obsolete tags are consistent
with the baseline is important"
}
]
}
```
```
{
"al.ruleSetPath": "custom.ruleset.json"
}
```
```
７ Note
```
```
In order to fully validate obsolete properties and attributes, it is recommended to
enable the rules AS0072 , AS0073 , AS0074 , AS0075 , and AS0076.
```
###### Setting up the AppSourceCop.json

```
{
"obsoleteTagVersion": "2.0"
}
```
### How to fix this diagnostic?


In the following example, the AppSourceCop is run against a baseline which has version
1.0 and expects the obsolete tag version for objects changing obsolete states to be 2.0.

```
JSON
```
Version of the extension used as baseline:

```
AL
```
Current version of the extension:

```
AL
```
### Example of code triggering this rule

```
{
"version": "1.0",
"obsoleteTagVersion": "2.0"
}
```
###### Modifying the obsolete tag for an object that does not

###### change obsolete state

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '1.0';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'Use table X instead.';
ObsoleteTag = '2.0';
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```

In the current version of the extension, the obsolete tag has changed from 1.0 to 2.0,
which is not allowed.

In the following example, the AppSourceCop is run against a baseline which has version
1.0 and expects the obsolete tag version for objects changing obsolete states to be 2.0.

```
JSON
```
Version 1.0 of the extension:

```
AL
```
The codeunit was marked as obsolete pending in the baseline and its obsolete tag value
does not change with the new version.

### Example of code not triggering this rule

```
{
"version": "1.0",
"obsoleteTagVersion": "2.0"
}
```
###### Preserving the obsolete tag for an object that does not

###### change obsolete state

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '1.0';
}
```
```
Version 2.0 of the extension:
```AL
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '1.0';
}
```
###### Adding a tag for an obsolete object that didn't have one -

###### lower than specified


Version 1.0 of the extension:

```
AL
```
The codeunit was marked as obsolete pending in the baseline without an obsolete tag.
The new version of the extension specifies an obsolete version which is lower than the
obsoleteTagVersion. This change is allowed by rule AS0074 in order to enable specifying

tags without fixing the baselines.

Version 1.0 of the extension:

```
AL
```
The codeunit was marked as obsolete pending in the baseline without an obsolete tag.
The new version of the extension specifies an obsolete version which is higher than the

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
}
```
```
Version 2.0 of the extension:
```AL
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '1.0';
}
```
###### Adding a tag for an obsolete object that didn't have one -

###### higher than specified

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
}
```
```
Version 2.0 of the extension:
```AL
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '3.0';
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

obsoleteTagVersion. This change is allowed by rule AS0074 in order to enable specifying
tags without fixing the baselines. However, a diagnostic will be reported by AS0072.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# AppSourceCop Warning AS0075

Article•10/01/2024

Obsolete Reason must be set.

Obsolete Reason must be set.

When an object, element, variable or procedure is marked as obsolete, you should also
specify an obsolete reason. The obsolete reason can be used to provide valuable
information, such as the reason for the obsoletion or a workaround to achieve the same
goal, to developers that are referencing it. The obsolete reason appears in the message
of the diagnostics AL0432 and AL0433 reported by the AL compiler when referencing
obsolete elements.

When the property Obsolete State is used to mark an object as Obsolete Pending or
Obsolete Removed, you need to also specify the property Obsolete Reason.

When the attribute Obsolete is used, you need to specify the obsolete reason attribute
parameter.

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - Table marked as Obsolete Pending

```
table 50100 MyTable
{
ObsoleteState = Pending;
fields
{
field( 50100 ; MyField; Integer) { }
```

```
AL
```
```
AL
```
```
AL
```
```
}
}
```
###### Example 2 - Procedure marked as Obsolete

```
codeunit 50100 MyCodeunit
{
[Obsolete]
procedure MyProcedure()
begin
// Business logic.
end;
}
```
### Code examples not triggering the rule

###### Example 1 - Table marked as Obsolete Pending

```
table 50100 MyTable
{
ObsoleteState = Pending;
ObsoleteReason = 'This table is being deprecated for reason X. Use table
Y instead.';
```
```
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
###### Example 2 - Procedure marked as Obsolete

```
codeunit 50100 MyCodeunit
{
[Obsolete('This procedure is being deprecated for reason X. Use
procedure Y instead.')]
procedure MyProcedure()
begin
// Business logic.
```

#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Hidden AS0076

Article•10/01/2024

Obsolete Tag format.

Obsolete Tag must have a specific format.

The ObsoleteTag property and attribute parameter values are not validated by the AL
compiler. However it is possible to setup the AppSourceCop to verify them using a
Regex expression.

The diagnostics for rule AS0076 are hidden by default, so you first have to use a ruleset
in order to surface them.

For example, the following ruleset turns the diagnostic for rule AS0076 into an error.

```
JSON
```
```
JSON
```
## Description

## Remarks

## Setting up AppSourceCop to validate the

## Obsolete Tag

## Enabling the rule using a ruleset

```
{
"name": "My custom ruleset",
"rules": [
{
"id": "AS0076",
"action": "Error",
"justification": "Validating that obsolete tags are formated
properly is important"
}
]
}
```

By default, the rule will validate that the specified obsolete tags are following the
pattern (\\d+)\\.(\\d+).

However, it is possible to specify a custom pattern as a regular expression using the
obsoleteTagPattern property in the AppSourceCop.json. The property
obsoleteTagPatternDescription can be used in order to provide a human readable

version of the expected pattern. The pattern description is used when reporting
diagnostics.

```
JSON
```
In order to fix this diagnostic, make sure that your obsolete tags are matching the
expected obsoleteTagPattern.

For instance, when using the default obsolete tag pattern, two diagnostics will be
reported by rule AS0076 because the obsolete tag property and the obsolete tag
attribute parameter values do not respect the format Major.Minor.

```
AL
```
```
{
"al.ruleSetPath": "custom.ruleset.json"
}
```
```
７ Note
```
```
In order to fully validate obsolete properties and attributes, we recommend
enabling the rules AS0072 , AS0073 , AS0074 , AS0075 , and AS0076.
```
###### Setting up the AppSourceCop.json

```
{
"obsoleteTagPattern": "^[A-Z]{3}$",
"obsoleteTagPatternDescription": "Three upper case letters"
}
```
### How to fix this diagnostic?

```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The code should be fixed a follows:

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
ObsoleteTag = 'Next major';
[Obsolete('Use function Y instead', 'Next spring')]
procedure MyProcedure()
begin
end;
}
```
```
codeunit 50100 MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use codeunit X instead.';
ObsoleteTag = '17.0';
[Obsolete('Use function Y instead', '17.0')]
procedure MyProcedure()
begin
end;
}
```
```
７ Note
```
```
The version to specify when using the default obsolete tag pattern is validated by
the rules AS0072 and AS0074.
```
### Related information

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0077

Article•10/01/2024

Adding a var modifier in events is not allowed

Adding a var modifier in events is not allowed as it might break the runtime behavior of
extensions subscribing to it.

This error ensures that the behavior of events remains consistent and predictable.
Adding a var modifier to an event parameter can alter how the parameter is handled,

potentially causing issues for extensions that subscribe to the event. These extensions
might not be designed to handle parameters passed by reference, leading to
compatibility issues and runtime errors. Maintaining the original parameter passing
mechanism (by value) ensures that the event's behavior remains stable and that
dependent extensions continue to function as expected.

To resolve this error, follow these steps:

1. Locate the event in your code where the var modifier has been added to a
    parameter.
2. Modify the event definition to remove the var modifier from the parameter.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0078

Article•10/01/2024

Adding or removing a var modifier in external procedures is not allowed

Adding or removing a var modifier in public procedures is not allowed as it might break
the runtime behavior of extensions calling it.

This error ensures that the behavior of public procedures remains consistent and
predictable. Adding or removing a var modifier can significantly change how

parameters are handled within a procedure. Extensions that call these procedures may
rely on the original parameter passing mechanism (by value or by reference). Altering
this mechanism can cause compatibility issues, runtime errors, and unexpected behavior
in these extensions. Maintaining the original parameter passing mechanism ensures that
the procedure's behavior remains stable and that dependent extensions continue to
function as expected.

To resolve this error, follow these steps:

1. Locate the public procedure in your code where the var modifier has been added
    or removed from a parameter.
2. Modify the procedure definition to restore the original var modifier status of the
    parameter.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Warning AS0079

Article•08/26/2024

An affix is required for procedures defined in extension objects.

An affix is required for procedures defined in extension objects, because it prevents
breaking dependent extensions that reference it in case a procedure with the same
signature is introduced by the base object or by another extension.

In order to avoid name clashes for procedures added by your extension objects (i.e table
extension, page extension) and procedures added by other extensions, an affix must be
prepended or appended to the name of all new procedures in extension objects,
extension objects, and fields. For more information, see Benefits and Guidelines for
using a Prefix or Suffix.

For procedures that are introduced with the current version of the extension, appending
one of the mandatory affixes to the object's name will fix the diagnostic. Renaming
procedures which are not part of the baseline is allowed.

For procedures which already exist in the version of the extension used as baseline, it is
not possible to rename them. It is therefore not possible to append one of the
mandatory affixes. Instead, the offending object procedure be deprecated using the
Obsolete attribute and a new procedure whose name has one of the mandatory affixes
should be introduced instead.

For instance, if the baseline of the extension contains a codeunit without affix:

## Description

## Remarks

## How to fix this diagnostic?

## For new extension objects or new procedures

## For existing objects

**Example - Adding an affix to an existing procedure**


```
AL
```
The extension should be modified to:

```
AL
```
The following example involves three extensions; Foo, Bar, and Foobar.

Foo defines a table named that does not have any procedure:

```
AL
```
Bar depends on Foo and defines a table extension that introduces a procedure named
MyProcedure:

```
tableextension 50100 Foo_CustomerExtension extends Customer
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```
```
tableextension 50100 Foo_CustomerExtension extends Customer
{
[Obsolete('Use Foo_MyProcedure instead')]
procedure MyProcedure()
begin
// Re-direct calls to not break the runtime of dependent extensions.
Foo_MyProcedure();
end;
```
```
procedure Foo_MyProcedure()
begin
// Business logic.
end;
}
```
### Example of issues detected by this rule

```
table 10 Foo_Table
{
fields
{
field( 1 ; MyField; Integer) { }
}
}
```

```
AL
```
Foobar depends on both Foo and Bar and defines a procedure referencing MyProcedure
from Bar:

```
AL
```
In a later version, the base extension Foo introduces a new method named Foo on the
table:

```
AL
```
When compiling the extension Bar, the AL compiler reports now a warning similar to
AL0523: The 'Table Bar_Table' already defines a method called 'MyProcedure' with
the same parameter types.. The runtime behavior of your extension is still preserved

though as it will run the procedure defined in the table extension.

```
tableextension 50100 Bar_TableExtension extends Foo_Table
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```
```
tableextension 50120 Foobar_TableExtension extends Foo_Table
{
procedure Foobar_SomeProcedure()
begin
// Calls into MyProcedure from Bar
MyProcedure();
end;
}
```
```
table 10 Foo_Table
{
fields
{
field( 1 ; MyField; Integer) { }
}
```
```
procedure MyProcedure()
begin
// Business logic.
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

When compiling the extension Foobar, the compilation fails because the AL compiler
reports an error similar to AL0196: The call is ambiguous between the method
'MyProcedure()' defined in TableExtension 'Bar_CustomerExtension' by the extension

'Bar' and the method 'MyProcedure()' defined in Table 'Foo_Table' by the extension

'Foo.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# AppSourceCop Error AS0080

Article•10/01/2024

Fields must not decrease in length

Decreasing the length of a field is not allowed. This might break the upgrade of existing
installations and dependent extensions.

The changes validated by this rule aren't allowed because they are destructive changes
for the sync engine. These changes might also break the runtime of dependent
extensions.

The validation of the length of table fields was previously done with AS0004 and has
now been split into two different rules:

```
AS0080 - which validates against decreasing the length of fields
AS0086 - which validates against increasing the length of fields
```
Reverting the change will fix this diagnostic. If decreasing the length of the field is
required, the recommended approach is to mark the field as Obsolete Pending and
introduce a new field with the desired length. Once all dependent extensions have
uptaken the new field, you can mark the the original one as Obsolete Removed.

Version 1.0 of the extension:

## Description

## Remarks

```
） Important
```
```
If the field is part of the primary key, this is validated by AS0118.
```
## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - Decreasing the length of a field


#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the type of the field MyField has changed from Text[50] to Text[25]. As

this is a breaking change, if version 1.0 was installed on a tenant, it won't be possible to
synchronize and upgrade the version 2.0 of the extension. Moreover, if a dependent
extension uses this field, this change of length can lead to runtime exceptions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ]) { }
}
}
```
```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 25 ]) { }
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0081

Article•10/01/2024

InternalsVisibleTo should not be used as a security feature.

The InternalsVisibleTo setting will expose your internal objects to any extension with the
given name, publisher, and ID. Access modifiers are not designed to be used as a
security boundary, but for API development.

For more information, see JSON Files.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0082

Article•10/01/2024

It is not allowed to rename an enum value.

Renaming an enum value is not allowed. Name changes are not allowed because it
might break the upgrade of existing installations and dependent extensions.

This error ensures that the names of enum values remain consistent across different
versions of an extension. Renaming an enum value can cause significant issues during
the upgrade process, as existing installations and dependent extensions may rely on the
original enum value names. Changing these names can lead to data inconsistencies,
runtime errors, and unexpected behavior in dependent extensions. Maintaining the
original names of enum values ensures compatibility and stability across upgrades.

To resolve this error, follow these steps:

1. Locate the enum value in your code that has been renamed.
2. Restore the original name of the enum value.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

# AppSourceCop Error AS0083

Article•10/01/2024

It is not allowed to delete a value from an enum.

Deleting an enum value is not allowed, unless the enum is marked as obsolete. This
restriction prevents dependent extensions from breaking, if they use the enum value.

This error ensures that enum values remain consistent and available across different
versions of an extension. Deleting an enum value can cause significant issues for
dependent extensions that rely on that value. These extensions may fail to function
correctly if the expected enum value is missing, leading to runtime errors and
unexpected behavior. By marking an enum value as obsolete instead of deleting it, you
provide a transition period during which dependent extensions can adapt to the change
without breaking.

To resolve this error, follow these steps:

1. Locate the enum value in your code that has been deleted.
2. Re-add the deleted enum value to the enum definition.
3. If the enum value should no longer be used, mark it as obsolete instead of deleting
    it.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0084

Article•10/01/2024

The ID range assigned to the extension must be within the allowed range

The ID range assigned to the extension must be within the range allowed for AppSource
applications.

This rule validates that the ID range specified in the app.json of your extension is
contained within the range allowed for AppSource application.

For more information about the object ID ranges in Business Central, see Object ranges
in Dynamics 365 Business Central.

For more information about the properties in the app.json file, see JSON files.

If you're targeting the AppSource marketplace, you need to update the ID range in your
app.json file with the one that Microsoft provided you with.

If you aren't targeting the AppSource marketplace, you can suppress this rule using
rulesets.

## Description

## Remarks

## How to fix this diagnostic?

```
７ Note
```
```
If you're targeting the AppSource marketplace and don't have an ID range
assigned, follow the steps defined in Get started with building apps.
```
## Code example triggering the rule

## The ID range is outside the range allowed for AppSource

## applications


The app.json file of the extension:

```
JSON
```
The ID range specified isn't contained in the range allowed for AppSource applications.

The app.json file of the extension:

```
JSON
```
If the ID range is not specified, the default ID range is used. As the default ID range
spans outside the allowed ID range for AppSource applications, a diagnostic will be
reported.

The app.json file of the extension:

```
JSON
```
```
{
[...]
"idRanges": [
{
"from": 50100 ,
"to": 50149
}
[...]
]
}
```
###### The ID range isn't specified

```
{
[...]
}
```
### Code example not triggering the rule

```
{
[...]
"idRanges": [
{
"from": 1000000 ,
"to": 1000100
}
[...]
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The ID range specified is included in the range allowed for AppSource applications.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
]
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Warning AS0085

Article•10/01/2024

Use the 'application' property instead of specifying explicit dependencies.

The 'application' property should be used for expressing a dependency on the 'Base
Application' or the 'System Application' instead of explicit dependencies. See
https://learn.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-
application-app-file for additional information.

This rule reports a diagnostic when the app.json of the extension specifies a
dependency on the 'Base Application' or 'System Application' extensions by Microsoft.

For more information about the benefits of using the application property, see The

Microsoft_Application.app file.

For more information about the properties in the app.json, see JSON files.

In order to fix this diagnostic, you have to replace the dependencies specifed on the
'Base Application' and 'System Application' in the dependencies property by the
application property in the app.json of the extension.

The app.json file of the extension:

```
JSON
```
## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
{
[...]
"dependencies": [
{
"appId": "437dbf0e-84ff-417a-965d-ed2bb9650972",
"name": "Base Application",
"publisher": "Microsoft",
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The app.json file of the extension:

```
JSON
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
"version": "15.3.0.0"
},
{
"appId": "63ca2fa4-4f03-4f2b-a480-172fef340d3f",
"name": "System Application",
"publisher": "Microsoft",
"version": "15.3.0.0"
}
],
[...]
}
```
### Code example not triggering the rule

```
{
[...]
"application": "17.0.0.0",
[...]
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Warning AS0086

Article•10/01/2024

Fields must not increase in length

Increasing the length of a field is not allowed as it might break the runtime behavior of
dependent extensions referencing it.

The validation of the length of table fields was previously done with AS0004 and has
now been split into two different rules:

```
AS0080 - which validates against decreasing the length of fields
AS0086 - which validates against increasing the length of fields
```
Reverting the change will fix this diagnostic. If increasing the length of the field is
required, the recommended approach is to mark the field as Obsolete Pending, and in a
later app version, remove that state again, and just increase the field length and remove
the Obsolete Pending state.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ]) { }
}
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
In version 2.0, the type of the field MyField has changed from Text[50] to Text[150]. If

a dependent extension uses this field, this can lead to runtime exceptions. For instance,
if it assigns it to a variable of type Text[50].

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 150 ]) { }
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

# AppSourceCop Warning AS0087

Article•10/01/2024

Translations of enum value captions must not contain commas

Translations of enum value captions must not contain commas. Commas in captions will
result in values with wrong captions both in the UI and potential unexpected results in
connection with formatting and evaluating enums.

This warning ensures that translations of enum value captions don't include commas,
which can cause issues in the user interface and during the processing of enums.
Commas can interfere with the correct display and handling of enum values, leading to
misleading or incorrect information being shown to users. Additionally, commas can
cause problems when enums are formatted or evaluated programmatically, potentially
leading to unexpected behavior or errors.

To resolve this warning, follow these steps:

1. Locate the enum value captions in your code that contain commas in their
    translations.
2. Modify the translations to remove any commas from the captions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## How to fix this diagnostic?

## Related information


Provide product feedback

```
 Yes  No
```

# AppSourceCop Error AS0088

Article•10/01/2024

Objects with an ID that can be referenced and which have been published must not be
deleted.

Objects that can be referenced by ID and which have been published must not be
deleted. This might break the upgrade of existing installations and dependent
extensions.

Reverting the change will fix this diagnostic. If deleting the object is required, the
recommended approach is to mark it first as ObsoleteState Pending. You can then
remove the object in a later version, or mark it as ObsoleteState Removed if the object is
a table. You cannot mark a table ObsoleteState = Removed if the table is not
ObsoleteState = Pending in the previous version.

Version 1.0 of the extension:

```
AL
```
In version 2.0 of the extension, codeunit 50120 has been deleted. This will trigger rule
AS0088.

## Description

## How to fix this diagnostic?

## Code Examples

## Example 1: Deleting a Codeunit triggers the rule

```
codeunit 50120 Foo_MyCodeunit
{
procedure MyProcedure()
begin
// Business logic.
end;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 3.0 of the extension, codeunit 50120 has been deleted. This is okay, because
codeunit 50120 previously had been marked with ObsoleteState = Pending informing
developers to use "50121 Foo_MyNewCodeunit" instead.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

###### Example 2: Deleting an obsolete pending Codeunit

```
codeunit 50120 Foo_MyCodeunit
{
ObsoleteState = Pending;
ObsoleteReason = 'Use 50121 Foo_MyNewCodeunit instead.';
procedure MyProcedure()
begin
// Business logic.
end;
}
```
```
codeunit 50121 Foo_MyNewCodeunit
{
procedure SomeProcedure()
begin
// Business logic.
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0089

Article•10/01/2024

Objects that can be referenced and which have been published must not be deleted.

Objects that can be referenced and which have been published must not be deleted.
This might break the upgrade of existing installations and dependent extensions.

Reverting the change will fix this diagnostic. If deleting or renaming the object is
required, the recommended approach is to mark it first as ObsoleteState Pending; if you
are performing a rename, this is where you would introduce a new object with the new
name. You can then mark the old object as ObsoleteState Removed in a later version.

Version 1.0 of the extension:

```
AL
```
## Description

## How to fix this diagnostic?

```
７ Note
```
```
This rule treats renaming and deleting as if it was the same action. The
AppSourceCop analyzer cannot track renaming of objects without an ID.
```
## Code Examples

## Example 1: Deleting a Page Customization triggers the

## rule

```
pagecustomization Foo_MyPageCustomization customizes "Customer List"
{
layout
{
modify(Name)
{
Visible = false;
}
```

In version 2.0 of the extension, Foo_MyPageCustomization has been deleted. This will

trigger rule AS0089.

Version 1.0 of the extension:

```
AL
```
In version 2.0 of the extension:

```
AL
```
The page customization FOO_IExampleInterface has been renamed, this will trigger rule

AS0089.

Version 2.0 of the extension:

```
AL
```
```
}
}
```
###### Example 2: Renaming an Interface triggers the rule

```
interface FOO_IExampleInterface
{
procedure ExampleProcedure() : Text
}
```
```
interface FOO_IMyInterface
{
procedure ExampleProcedure() : Text
}
```
###### Example 3: Deleting an obsolete pending Page

###### Customization

```
interface FOO_IMyInterface
{
procedure ExampleProcedure(): Text
ObsoleteState = Pending;
ObsoleteReason = 'Use FOO_IExampleInterface instead.';
}
interface FOO_IExampleInterface
{
```

#### Feedback

**Was this page helpful?**

Provide product feedback

In version 3.0 of the extension, FOO_IMyInterface has been deleted. This is okay, because

```
FOO_IMyInterface previously had been marked with ObsoleteState = Pending informing
```
developers to use "FOO_IExampleInterface" instead.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
procedure SomeProcedure(): Text
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0090

Article•10/01/2024

Objects that can be referenced and which have been published must not be renamed.

Objects than can be referenced and which have been published must not be renamed
because it might break the upgrade of existing installations and dependent extensions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0091

Article•08/26/2024

One or more dependencies of the previous version of the extension could not be found.

One or more dependencies of the previous version of the extension, used as a baseline
for detecting breaking changes, could not be found in the package cache folder.

This rule validates that the dependencies for the version of the extension specified as a
baseline for detecting breaking changes can be found in the baseline package cache
folder.

For more information on how to set up the AppSourceCop to detect breaking changes,
see AS0003.

If you do not want to detect breaking changes in your extension, remove the property
version in the AppSourceCop.json file.

If you want to detect breaking changes, verify that the version specified in the
AppSourceCop.json file is correct and that the baseline's dependencies can be found in
the baseline package cache.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

```
７ Note
```
```
The rule AS0003 verifies that the baseline can be found in the baseline package
cache folder.
```
## Setting up AppSourceCop to detect breaking changes

## How to fix this diagnostic?

## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# AppSourceCop Warning AS0092

Article•10/01/2024

The app.json file must specify an Azure Application Insights resource.

The app.json file must specify an Azure Application Insights resource for monitoring
operations related to this extension. See
https://learn.microsoft.com/dynamics365/business-central/dev-
itpro/administration/telemetry-overview for additional information.

This diagnostic can be fixed by specifying an Azure Application Insights resource for the
extension.

For more information about enabling Application Insights, see Monitoring and
Analyzing Telemetry and Environment Telemetry.

For additional information about the manifest of extensions (app.json), see JSON Files.

If your extension is targeting runtime 7.2 (i.e. Business Central 2021 release wave 1

update 18.2), you can fix this diagnostic by specifying the connection string of the Azure
Application Insights resource setup to monitor the operations related to this extension.

```
JSON
```
If your extension is targeting a lower runtime version than 7.2, you can fix this

diagnostic by specifying the instrumentation key of the Azure Application Insights
resource setup to monitor the operations related to this extension.

## Description

## How to fix this diagnostic?

## When targeting runtime version 7.2 or higher?

```
{
"applicationInsightsConnectionString": "<your-azure-application-insight-
connection-string>"
}
```
## When targeting a runtime version lower than 7.2?


Or before 7.2 - Business Central 2021 release wave 1 update 18.2:

```
JSON
```
This rule is triggered when both the 'applicationInsightsConnection' and the
'applicationInsightsKey' properties are not specified in the manifest (app.json) of the
extension, or when its value is set to the empty string/GUID as shown below:

```
JSON
```
```
JSON
```
This rule is also triggered when specifying 'applicationInsightsKey' and targeting a
runtime version higher or equal to 7.2.

```
JSON
```
Using Application Insights provides telemetry to troubleshoot, understand, and fix issues
related to your extension in production.

```
{
"applicationInsightsKey": "<your-azure-application-insight-
instrumentationKey>"
}
```
### Code examples triggering the rule

```
{
"applicationInsightsConnectionString": ""
}
```
```
{
"applicationInsightsKey": "00000000-0000-0000-0000-000000000000"
}
```
```
{
"applicationInsightsKey": "241514be-e378-4455-a2d3-bf7e40b7d41d",
"runtime": "7.2"
}
```
### Benefits of using the Application Insights


#### Feedback

**Was this page helpful?**

Provide product feedback

The Azure Application Insights resource specified in the manifest of the extension
submitted to AppSource will be used to log detailed information about the validation
process for your AppSource submission. For more information, see Analyzing
AppSource Submission Validation Trace Telemetry.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Usage of Application Insights during the

### validation of AppSource submissions

### Related information

```
 Yes  No
```

# AppSourceCop Warning AS0094

Article•10/01/2024

Permission Sets should not be defined in XML files.

Permission sets should not be defined in XML. Instead, use the dedicated AL object for
'PermissionSet'.

```
XML
```
For a table called "Floor Manager" with object ID 70001, we can convert the above
permissions defined in XML into a permission set object defined in AL as shown below:

```
AL
```
## Description

## Example of XML file triggering the rule

```
<?xml version="1.0" encoding=""utf-8""?>
<PermissionSets>
<PermissionSet RoleID="TestProjectPermissionSet" RoleName="Default">
<Permission>
<ObjectType> 8 </ObjectType>
<ObjectID> 70001 </ObjectID>
<ReadPermission> 1 </ReadPermission>
<InsertPermission> 1 </InsertPermission>
<ModifyPermission> 1 </ModifyPermission>
<DeletePermission> 1 </DeletePermission>
<ExecutePermission> 0 </ExecutePermission>
<SecurityFilter />
</Permission>
</PermissionSet>
</PermissionSets>
```
## Converted into a PermissionSet object

```
permissionset  50130  MyPermissionSet
{
    Assignable = true;
Caption = 'My PermissionSet';
   Permissions =
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The RIMD access allows access to **R** ead, **I** nsert, **M** odify, and **D** elete entries in the table.

This can be modified by adding and removing letters corresponding to the first letter of
the permission that you want to (dis)allow. This permission set can then be assigned to
users/roles.

You can convert XML permission sets to AL objects. For more information, see
Upgrading Permissions Sets and Permissions.

PermissionSet Object AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
       tabledata "Floor Manager" = RIMD;
}
```
### How to fix this diagnostic?

### Related information

```
 Yes  No
```

# AppSourceCop Error AS0095

Article•08/26/2024

The access modifier of a table field cannot be changed to a value that provides less
access.

The access modifier of a table field cannot be changed to a value that provides less
access because it will break dependent extensions. You can only change the accessibility
to provide more access.

This rule verifies that the Access property of a field in a table or table extension has not
been reduced between revisions. This rule only validates table fields if the table Access

property is set to Public in the baseline extension. For more information about different

access levels for both fields and tables, see Using Access Modifiers in AL.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

## Description

## Remarks

## Code examples triggering the rule

## Example 1: Reducing the Access Level to lower than Public

```
table 50122 MyTable
{
Access = Public; // If omitted the default value is Public
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Public;
}
}
}
```

```
AL
```
Reducing the Access of a field in a Table will result in breaking extensions that are

already using the field.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
table 50122 MyTable
{
Access = Public; // If omitted the default value is Public
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Protected; // or Local, Internal
}
}
}
```
###### Example 2: Reducing the Access Level to lower than

###### Protected

```
table 50122 MyTable
{
Access = Public; // If omitted the default value is Public
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Protected;
}
}
}
```
```
table 50122 MyTable
{
Access = Public; // If omitted the default value is Public
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Local; // or Internal
```

Reducing the Access level of the field might result in breaking existing scenarios where

a dependent table extension defined in other application extension references this field.
This will result in compilation error AL0161. The same rule applies to fields defined in a

table extension.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
}
}
}
```
###### Example 3: Reducing the Access Level to lower than

###### Public of a field defined in TableExtension

```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Public;
}
}
}
```
```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Protected; // or Local, Internal
}
}
}
```
### Code Examples that don't trigger the rule


Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
Changing the Access level from Internal to Public on MyTable means that we are

exposing the table for first time, so we cannot reduce the access level of the field since it
has already indirectly been Internal.

Version 1.0 of the extension:

```
AL
```
###### Example 1: Exposing the table for the first time

```
table 50122 MyTable
{
Access = Internal;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Public;
}
}
}
```
```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Protected; // or any other access modifier
}
}
}
```
###### Example 2: Changing the Access level from Local to

###### Internal or vice versa

```
table 50122 MyTable
{
```

Version 2.0 of the extension:

```
AL
```
Changing Access level from Local to Internal or vice versa will not trigger the rule.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Local;
}
}
}
```
```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Internal;
}
}
}
```
###### Example 3: Changing the Access Level to Public or

###### Protected from lower Access Level

```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Local; // or Internal
}
}
}
```

```
AL
```
Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Public; // or Protected
}
}
}
```
###### Example 4: Changing the Access Level to Public from

###### Protected

```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Protected;
}
}
}
```
```
table 50122 MyTable
{
Access = Public;
fields
{
field( 1 ; FirstField; Code[ 1 ])
{
Access = Public;
}
}
}
```

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
Version 1.0 of the extension:

```
AL
```
###### Example 5: Changing the Access Level to Public or

###### Protected from a lower access level in a table extension

```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Local; // or Internal
}
}
}
```
```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Public; // or Protected
}
}
}
```
###### Example 6: Changing the Access Level to Public from

###### Protected in a table extension

```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Protected;
}
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
}
}
```
```
tableextension 50126 MyTableExtension extends MyTable
{
fields
{
field( 2 ; OtherField; Integer)
{
Access = Public;
}
}
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0096

Article•10/01/2024

The name of an extension cannot be changed.

The name of an extension cannot be changed for extensions targeting a runtime version
lower than '8.0' in their app.json file. This will break the upgrade of existing installations
and dependent extensions.

Changing the identity of extensions is only supported in Business Central starting from
version 2021 release wave 2 which corresponds to the AL runtime version 8.0, see JSON
Files. For more information about what makes up the identity of an app, see App
Identity.

In order to fix this diagnostic, you must either:

```
change the name of the extension in the app.json to match the name used in the
baseline,
update the runtime version in the app.json to be 8.0 or higher.
```
Version 1.0 of the extension:

```
JSON
```
Version 2.0 of the extension:

## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
{
"name": "Extension Name",
"publisher": "Publisher Name",
"version": "1.0.0.0",
"runtime": "7.2",
// other properties
}
```

```
JSON
```
In version 2.0, the extension has been renamed from Extension Name to New Extension

Name while still targeting runtime 7.2. The rename is not allowed.

Version 1.0 of the extension:

```
JSON
```
Version 2.0 of the extension:

```
JSON
```
In version 2.0, the extension has been renamed from Extension Name to New Extension

Name and the runtime version has been changed to 8.0. The rename is allowed.

```
{
"name": "New Extension Name",
"publisher": "Publisher Name",
"version": "2.0.0.0",
"runtime": "7.2",
// other properties
}
```
### Code example not triggering the rule

```
{
"name": "Extension Name",
"publisher": "Publisher Name",
"version": "1.0.0.0",
"runtime": "7.2",
// other properties
}
```
```
{
"name": "New Extension Name",
"publisher": "Publisher Name",
"version": "2.0.0.0",
"runtime": "8.0",
// other properties
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions
App Identity

```
 Yes  No
```

# AppSourceCop Error AS0097

Article•08/26/2024

The publisher name of an extension cannot be changed.

The publisher name of an extension cannot be changed for extensions targeting a
runtime version lower than '8.0' in their app.json file. This will break the upgrade of
existing installations and dependent extensions.

Changing the identity of extensions is only supported in Business Central starting from
version 2021 release wave 2 which corresponds to the AL runtime version 8.0, see JSON
Files. For more information about what makes up the identity of an app, see App
Identity.

In order to fix this diagnostic, you must either:

```
change the publisher of the extension in the app.json to match the publisher name
used in the baseline,
update the runtime version in the app.json to be 8.0 or higher.
```
Version 1.0 of the extension:

```
JSON
```
Version 2.0 of the extension:

## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
{
"name": "Extension Name",
"publisher": "Publisher Name",
"version": "1.0.0.0",
"runtime": "7.2",
// other properties
}
```

```
JSON
```
In version 2.0, the publisher has been renamed from Publisher Name to New Publisher

Name while still targeting runtime 7.2. The rename is not allowed.

Version 1.0 of the extension:

```
JSON
```
Version 2.0 of the extension:

```
JSON
```
In version 2.0, the publisher has been renamed from Publisher Name to New Publisher

Name and the runtime version has been changed to 8.0. The rename is allowed.

```
{
"name": "Extension Name",
"publisher": "New Publisher Name",
"version": "2.0.0.0",
"runtime": "7.2",
// other properties
}
```
### Code example not triggering the rule

```
{
"name": "Extension Name",
"publisher": "Publisher Name",
"version": "1.0.0.0",
"runtime": "7.2",
// other properties
}
```
```
{
"name": "Extension Name",
"publisher": "New Publisher Name",
"version": "2.0.0.0",
"runtime": "8.0",
// other properties
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions
App Identity

```
 Yes  No
```

# AppSourceCop Warning AS0098

Article•10/01/2024

An affix is needed.

An affix is needed.

In order to avoid name clashes for objects added by your extension and objects added
by other extensions, an affix must be prepended or appended to the name of all new
application objects, extension objects, and fields. For more information, see Benefits and
Guidelines for using a Prefix or Suffix.

The following object members are validated by AS0098:

```
Enum Values defined in Enum Extension objects
Data Items defined in Report Extension objects
Columns defined in Report Extension objects
Labels defined in Report Extension objects
Keys defined in Table Extension objects on table extension fields
```
Other AL objects and object members are validated by AS0011.

For objects that are introduced with the current version of the extension, appending one
of the mandatory affixes to the object's name will fix the diagnostic. Renaming objects

## Description

```
７ Note
```
```
This rule mimics the behavior of AS0011 for a limited set of objects members for
which AS0011 wasn't enforced when they were introduced in AL. Having them
reported as a separate rule allows more granularity, especially in regard to AL code
not respecting the use of affixes prior to the implementation of this rule.
```
## Which object members are validated?

## When to fix this diagnostic?

## For new object members


#### Feedback

**Was this page helpful?**

Provide product feedback

which are not part of the baseline is allowed.

For objects which already exist in the version of the extension used as baseline, it is not
possible to rename them. It is therefore not possible to append one of the mandatory
affixes. Instead, the offending object should be deprecated using the ObsoleteState
property and a new object whose name has one of the mandatory affixes should be
introduced.

For detailed examples, see AS0011.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

###### For existing objects

```
） Important
```
```
Introducing a new enum value can be a breaking change if this enum value is
stored in the database. You must carefully assess the impact of your changes before
introducing a new enum value. This implies writing upgrade code for your app and
for the dependent extensions storing this enum value in their own tables.
```
### Related information

```
 Yes  No
```

# AppSourceCop Info AS0099

Article•08/26/2024

The member ID should be within the allowed range

The member ID should be within the allowed range and outside the range allocated to
per-tenant customizations.

In order to avoid ID clashes for objects added by your extension and objects added by
other extensions, you must respect the ID range specified in the app.json file of your
extension when declaring new AL objects. For more information on ID ranges in
Business Central, see Object Ranges.

The following object members are validated by AS0098:

```
Enum Values defined in Enum Extension objects
Fields defined in Table Objects
```
Other AL objects and object members are validated by AS0013.

For objects that are introduced with the current version of the extension, changing the
ID of the object will fix the diagnostic. Changing the ID of objects which are not part of
the baseline is allowed.

## Description

```
７ Note
```
```
This rule mimics the behavior of AS0013 for a limited set of objects members for
which AS0013 wasn't enforced when they were introduced in AL. Having them
reported as a separate rule allows more granularity, especially in regards to AL code
not respecting the use of affixes prior to the implementation of this rule.
```
## Which object members are validated?

## When to fix this diagnostic?

## For new object members


#### Feedback

**Was this page helpful?**

Provide product feedback

For objects which already exist in the version of the extension used as baseline, it is not
possible to change their ID. Instead, the offending object should be deprecated using
the ObsoleteState property and a new object whose ID is within the range allocated for
the extension should be introduced.

For detailed examples, see AS0013.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

###### For existing objects

```
） Important
```
```
Changing the ID of an enum value has an impact on the data stored in the
database. You must carefully assess the impact of your changes before changing
the ID of an enum value. This implies writing upgrade code for your app and for the
dependent extensions storing this enum value in their own tables.
```
### Related information

```
 Yes  No
```

# AppSourceCop Error AS0100

Article•10/01/2024

The 'application' property must be specified in the app.json file.

The 'application' property in the app.json file must be specified on apps targeting the
AppSource marketplace.

The application property is used in order to compute the minimum release of Business

Central for which your extension will be validated and made available for.

For more information about the computation of the minimum release targeted by an
AppSource submission, see Technical Validation Checklist.

For more information about the usage and benefits of the application, see The

Microsoft_Application.app File.

In order to fix this diagnostic, you have to specify the application property in the
app.json of the extension.

The app.json file of the extension:

```
JSON
```
The app.json file of the extension:

## Description

## How to fix this diagnostic?

## Code example triggering the rule

```
{
"id": "<some-guid>",
"name": "My App",
"publisher": "My Publisher",
"version": "1.0.0.0"
}
```
## Code example not triggering the rule


#### Feedback

**Was this page helpful?**

Provide product feedback

```
JSON
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
{
"id": "<some-guid>",
"name": "My App",
"publisher": "My Publisher",
"version": "1.0.0.0",
"application": "19.0.0.0",
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0101

Article•10/01/2024

The 'Isolated' argument cannot be changed, added, or removed.

Any change to the 'Isolated' argument is disallowed because it may break dependent
extensions that have subscribed to the event.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0102

Article•08/26/2024

Cannot add a return value to a procedure

It is not allowed to add a return value to a publicly exposed procedure, because it might
break dependent extensions at runtime.

This rules validates that a return value has not been added to a publicly exposed
procedures. Other changes on the return types of procedures are validated by AS0023.

Reverting the change will fix this diagnostic. If changing the return type is required, the
recommended approach is to mark the procedure with the Obsolete attribute and
introduce a new one with the desired return type. In a future version, once all
dependent extensions have updated their code to not reference the obsolete procedure,
you can remove it.

In the following examples, the version 1.0 of the extension defines a procedure which
does not have a return type.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

```
７ Note
```
```
This rule also covers the cases related to the TryFunction attribute which implicitly
defines a Boolean return type.
```
## How to fix this diagnostic?

## Code examples triggering the rule

```
codeunit 50100 MyCodeunit
{
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure MyProcedure is now returning a boolean. It does not break

the compilation of dependent extensions because they were not consuming the return
type of the procedure. However, this change will break the runtime behavior of
dependent extensions that referencing this procedure and that have not been
recompiled.

Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure MyProcedure is now implictly returning a boolean. It does
not break the compilation of dependent extensions because they were not consuming
the return type of the procedure. However, this change will break the runtime behavior

```
procedure MyProcedure()
begin
end;
}
```
###### Example 1 - Adding a return type to a procedure

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure(): Boolean
begin
exit(true);
end;
}
```
###### Example 2 - Adding a TryFunction attribute to a

###### procedure

```
codeunit 50100 MyCodeunit
{
[TryFunction]
procedure MyProcedure()
begin
exit(true);
end;
}
```

of dependent extensions that referencing this procedure and that have not been
recompiled.

Version 1.0 of the extension:

```
AL
```
Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure is now implicitly returning a Boolean. The return type has
not changed.

Version 1.0 of the extension:

```
AL
```
### Code examples not triggering the rule

###### Example 1 - Adding a TryFunction attribute to a method

###### returning a boolean

```
codeunit 50100 MyCodeunit
{
procedure MyProcedure() : Boolean
begin
exit(true);
end;
}
```
```
codeunit 50100 MyCodeunit
{
[TryFunction]
procedure MyProcedure()
begin
exit(true);
end;
}
```
###### Example 2 - Removing a TryFunction attribute and adding

###### a boolean return type


#### Feedback

**Was this page helpful?**

Provide product feedback

Version 2.0 of the extension:

```
AL
```
In version 2.0, the procedure is now explicitly returning a Boolean. The return type has
not changed.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
codeunit 50100 MyCodeunit
{
[TryFunction]
procedure MyProcedure()
begin
exit(true);
end;
}
```
```
codeunit 50100 MyCodeunit
{
procedure MyProcedure() : Boolean
begin
exit(true);
end;
}
```
### Related information

```
 Yes  No
```

# AppSourceCop Warning AS0103

Article•10/01/2024

Table definitions must have a matching permission set.

Table definitions must have a matching permission set.

To prevent runtime issues caused by missing permissions, all table definitions in your
extension must be included in a permission set.

Permissions can be defined either by using XML, or by using AL permission set objects.

To generate XML permission sets, you can use the dedicated command in Visual Studio
Code:

1. Select Ctrl+Shift+P to open the command palette.
2. Select **AL: Generate permission set containing current extension objects**. This will
    generate the XML permission set for your extension.
3. Rebuild your extension by selecting Ctrl+Shift+B to package the permission
    set with your extension.

For more information about AL permission sets, see Permission Set Object.

For the following example, let's consider an extension that has the following source
code:

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code examples not triggering the rule

```
table 50100 MyTable
{
fields
{
field( 1 ; MyField; Integer) { }
```

```
XML
```
The XML permission set grants access to the table and thereby satisfies the validation.
However, the XML approach is discouraged by the AppSourceCop rule AS0094, in which
it is recommended instead to use the AL Permission Set object (see Example 2).

```
AL
```
The AL permission set grants access to the table and thereby satisfies the validation.

```
}
}
```
###### Example 1 - Permission defined in XML

```
<?xml version="1.0" encoding="utf-8"?>
<PermissionSets>
<PermissionSet RoleID="ALPROJECT15" RoleName="ALProject15">
<Permission>
<ObjectID> 50100 </ObjectID>
<ObjectType> 0 </ObjectType>
<ReadPermission> 1 </ReadPermission>
<InsertPermission> 1 </InsertPermission>
<ModifyPermission> 1 </ModifyPermission>
<DeletePermission> 1 </DeletePermission>
<ExecutePermission> 0 </ExecutePermission>
<SecurityFilter />
</Permission>
</PermissionSet>
</PermissionSets>
```
###### Example 2 - Permission defined in AL

```
permissionset 50100 MyPermissionSet
{
Assignable = true;
Permissions = tabledata MyTable = RIMD;
}
```
```
７ Note
```
```
You can grant access to all your tables using *. For instance tabledata * = R;
grants read access to all of them.
```

#### Feedback

**Was this page helpful?**

Provide product feedback

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0104

Article•10/01/2024

The extension name is not valid.

The extension name is not valid.

In order to fix this diagnostic, you must change the extension name in the manifest
(app.json) of your extension.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

## Description

## How to fix this diagnostic?

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0105

Article•10/01/2024

Object pending obsoletion contains an expired ObsoleteTag.

Objects that are pending obsoletion with an obsolete tag version lower than the
minimum set in the AppSourceCop.json file are not allowed.

When Microsoft obsoletes code, the obsolete tag is set to the version in which the
element is obsoleted. After an object has been marked as obsoleted, another 12 months
will pass before the object is actually removed - in some cases this can also be longer.

If the tag is set to, for example, '18.0', the code will still be present in versions 19 and

20. We will at the earliest remove the code in version 21. Assuming the code is removed
in version 21, this can happen right after version 20 was released, but could also happen
later during the release.

This rule helps you validate early if your app is ready for a given release of Business
Central without relying on Microsoft to actually remove the code.

Fore more information about deprecating code, see Microsoft Timeline for Deprecating
Code in Business Central.

By setting the obsoleteTagMinAllowedMajorMinor in the AppSourceCop.json, you can
validate that your extension does not reference any objects that are pending obsoletion
with an obsolete tag lower than the version you have specified.

If you want to validate that your extension is ready for version 21.0, then you must set

the obsoleteTagMinAllowedMajorMinor property to 18.0 since objects will remain

available for at least 12 months (2 releases) before being removed.

For example:

```
JSON
```
## Description

## Microsoft timeline for deprecating code

## How to enable the validation?


If you do not want to validate if your app is referencing obsolete objects with obsolete
tags lower than a given version, remove the property obsoleteTagMinAllowedMajorMinor

in the AppSourceCop.json file.

If you want to validate if your app is referencing obsolete objects with obsolete tags
lower than a given version, remove the references to obsolete code following the
instructions in the obsolete reason.

For the following examples, let's consider that you have an extension defining a
codeunit that references an obsolete pending page from another extension.

Your extension:

```
AL
```
Dependency extension:

```
AL
```
```
{
"obsoleteTagMinAllowedMajorMinor": "18.0"
}
```
```
） Important
```
```
Enabling this rule has a performance impact, especially on large projects. We do
not recommend keeping it enabled always, but we highly recommend enabling it in
order to remove references to obsolete pending objects that can potentially be
removed with the upcoming release of Business Central. After all object references
have been fixed, you can turn off the rule again.
```
### How to fix this diagnostic?

### Code examples

```
codeunit 50100 MyCodeunit
{
var
p: SomePage;
}
```

#### Feedback

If the obsoleteTagMinAllowedMajorMinor version is set to any version equal to 18.0 or
lower than 18.0, then no error is reported.

Example:

```
JSON
```
If the obsoleteTagMinAllowedMajorMinor version is set to any version higher than 18.0,

then an error is reported.

Example:

```
JSON
```
AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
page 50100 SomePage
{
ObsoleteState = Pending;
ObsoleteReason = 'Use page X instead.'
ObsoleteTag = '18.0';
}
```
###### Code example not triggering the rule

```
{
"obsoleteTagMinAllowedMajorMinor": "17.0"
}
```
###### Code example triggering the rule

```
{
"obsoleteTagMinAllowedMajorMinor": "19.0"
}
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0106

Article•10/01/2024

A variable belonging to the public API cannot be removed.

A variable that belongs to the public API cannot be removed, because it will break
dependent extensions referencing this variable.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0107

Article•10/01/2024

The access modifier of a variable that belongs to the public API cannot be changed to a
value that provides less access.

The access modifier of a variable that belongs to the public API cannot be changed to a
value that provides less access, because it will break dependent extensions.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0108

Article•10/01/2024

The type of a variable belonging to the public API cannot be changed.

The type of a variable that belongs to the public API cannot be changed, because it will
break dependent extensions.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0109

Article•10/01/2024

The type of the table has changed from Normal to Temporary.

The type of a table should not be changed from Normal to Temporary, because
synchronizing the app will fail if the table contains data. Make sure to remove all data
from the table before changing the table type to temporary.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0110

Article•10/01/2024

Permission set extensions should not include permissions for objects defined in another
application.

Permission set extensions should not include permissions for objects defined in another
application. This can pose a security risk by granting excessive privileges to users.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0111

Article•10/01/2024

Permission set extensions should not include permission sets defined in another
application.

Permission set extensions should not include permission sets from another application.
This can pose a security risk by granting excessive privileges to users.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0112

Article•10/01/2024

Permission set extensions should not include permission sets which include permissions
for objects defined in another application.

Permission set extensions should not include permission sets which include permissions
for objects defined in another application. This can pose a security risk by granting
excessive privileges to users.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0113

Article•10/01/2024

Permission set extensions should not include wildcard permissions.

Permission set extensions should not include wildcard permissions. Wildcard
permissions can pose a security risk by unintentionally granting excessive privileges to
users.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0114

Article•10/01/2024

The name of an external business event cannot be changed.

The name attribute parameter of an external business event cannot be changed because
it might break external subscribers.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0115

Article•10/01/2024

The obsolete state cannot change directly from 'No' to 'Removed'.

The obsolete state cannot change directly from 'No' to 'Removed'. This can break the
upgrade of existing installations and dependent extensions. Instead, the obsolete state
must be changed to 'Pending' in this version and changed to 'Removed' in a later
version.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0116

Article•10/01/2024

Source application for the moved symbol cannot be found.

The source application for this moved symbol cannot be found.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0117

Article•10/01/2024

Application object is moved without the use of PendingMove.

When an application object is moved we should first set the ObsoleteState to
PendingMove in a previous version of the extension.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# AppSourceCop Error AS0118

Article•08/26/2024

The length of a field part of the primary key cannot change.

Modifying the length of a field part of the primary key is not allowed.

The changes validated by this rule aren't allowed because they are destructive changes
for the synchronization engine. These changes might also break the runtime of
dependent extensions.

The validation of the length of table fields part of primary keys was previously done with
AS0080 and is now handled by this rule.

Reverting the change will fix this diagnostic.

Version 1.0 of the extension:

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - Decreasing the length of a field, which is part

## of the primary key

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ]) { }
}
keys
{
key(MyKey; MyField) { }
```

Version 2.0 of the extension:

```
AL
```
In version 2.0, the type of the field MyField has changed from Text[50] to Text[25].

Because this is a breaking change, if version 1.0 was installed on a tenant, it won't be
possible to synchronize and upgrade the version 2.0 of the extension. Moreover, if a
dependent extension uses this field, this change of length can lead to runtime
exceptions.

Version 1.0 of the extension:

```
AL
```
```
}
}
```
```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 25 ]) { }
}
keys
{
key(MyKey; MyField) { }
}
}
```
```
７ Note
```
```
When no primary key is explicitly defined in the table definition, the first field is
used as the primary key.
```
###### Example 2 - Increasing the length of a field, which is part

###### of the primary key

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 50 ]) { }
}
keys
{
```

#### Feedback

**Was this page helpful?**

Version 2.0 of the extension:

```
AL
```
In version 2.0, the type of the field MyField has changed from Text[50] to Text[100].

Even if the length has increased, this change is not supported because MyField is part of

the primary key MyKey. As this is a breaking change, if version 1.0 was installed on a

tenant, it won't be possible to synchronize and upgrade the version 2.0 of the extension.
Moreover, if a dependent extension uses this field, this change of length can lead to
runtime exceptions.

AppSourceCop Analyzer
Get Started with AL
Developing Extensions

```
field(MyKey; MyField) { }
}
}
```
```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Text[ 100 ]) { }
}
keys
{
field(MyKey; MyField) { }
}
}
```
```
７ Note
```
```
When no primary key is explicitly defined in the table definition, the first field is
used as primary key.
```
### Related information

```
 Yes  No
```

Provide product feedback


## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0119

Article•10/01/2024

The value of the MovedTo property in the source symbol does not match the
destination AppId.

The source symbol's MovedTo property value does not match the destination AppId.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0120

Article•10/01/2024

The value of the MovedFrom property in the destination object does not match the
source AppId.

The destination symbol's MovedFrom property value does not match the source AppId.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0121

Article•10/01/2024

When a symbol is moved the name must remain the same.

The name of the moved symbol in the source and the destination application is
different.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0122

Article•10/01/2024

Source symbol for the moved symbol cannot be found in the package with the given
AppId.

The source symbol for this moved symbol cannot be found in the package with the
given AppId.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0123

Article•10/01/2024

A key cannot be declared as clustered on an existing table.

A key cannot be declared as clustered on an existing table.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0124

Article•10/01/2024

Changing an extension object's target is not allowed.

Changing the target of an extension object that has been published is not allowed,
because this might break the dependent extensions.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Info AS0125

Article•10/01/2024

Changes the XLIFF translation ID are not allowed.

Changes affecting the XLIFF translation ID of an object or object member that has been
published are not allowed, because this will break the translations provided by
dependent extensions for your extension.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0126

Article•10/01/2024

InternalsVisibleTo should not specifying a different publisher name than the one of this
extension.

By specifying a different publisher name for your extension, you grant extensions from
that publisher the permission to access the internal features of your extension.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Warning AS0127

Article•10/01/2024

Objects should be placed in a namespace with at least two levels.

Objects should be placed in a namespace with at least two levels of nesting. This
minimizes conflicts with other applications and allows the object name to not use an
affix.

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0128

Article•10/01/2024

An interface must not be removed from the the list of extended interfaces on an
interface that has been published.

An interface must not be removed from the list of extended interfaces on an interface
that has been published, because dependent extensions may break

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# AppSourceCop Error AS0129

Article•10/01/2024

An interface must not be added to the the list of extended interfaces on an interface
that has been published.

An interface must not be added to the list of extended interfaces on an interface that
has been published, because dependent extensions may break

AppSourceCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# PerTenantExtensionCop Error PTE0001

Article•10/01/2024

Object ID must be in free range.

Object ID must be in free range.

This rule validates that all the object IDs defined in your extension are within range
50,000-99,999 that is allocated for per-tenant extensions. For more information about
the ID ranges for extensions, see Object Ranges.

You must change the ID of the object or table field validated in order to use an ID within
the range 50,000-99,999.

```
AL
```
The codeunit MyCodeunit has the ID 10 which is not valid because it is outside the
allowed range.

```
AL
```
## Description

## Remarks

## How to fix this diagnostic?

## Code example triggering the rule

```
codeunit 10 MyCodeunit
{
// Business logic
}
```
## Code examples not triggering the rule

```
codeunit 50100 MyCodeunit
{
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The codeunit MyCodeunit has the 50100 10 which is valid because it is within the

allowed range.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

```
// Business logic
}
```
### Related information

```
 Yes  No
```

# PerTenantExtensionCop Error PTE0002

Article•08/26/2024

Field ID must be in free range.

Field ID must be in free range.

This rule validates that all table field IDs defined in your extension are within range
50,000-99,999 that is allocated for per-tenant extensions. For more information about
the ID ranges for extensions, see Object Ranges.

You must change the ID of the object or table field validated in order to use an ID within
the range 50,000-99,999.

```
AL
```
## Description

## Remarks

```
７ Note
```
```
When a new AL table, you are also allowed to use the range 0-49,999 for the ID of
your table fields.
```
## How to fix this diagnostic?

## Code examples triggering the rule

## Example 1 - A table field ID outside the range 50,000-

## 99,999

```
table 50100 MyTable
{
fields
{
field( 1000000 ; MyField; Integer) { }
```

The table field MyField has the ID 1000000 which is not valid because it is outside the

allowed range.

```
AL
```
```
AL
```
The table field MyField has the ID 50100 which is valid because it is within the allowed

range.

```
AL
```
```
}
}
```
###### Example 2 - A table extension field ID in the ID range 0-

###### 49,999

```
tableextension 50100 MyTableExt extends MyTable
{
fields
{
field( 10 ; MyExtField; Integer) { }
}
}
```
### Code examples not triggering the rule

###### Example 1 - A table field ID within the range 50,000-

###### 99,999

```
table 50100 MyTable
{
fields
{
field( 50100 ; MyField; Integer) { }
}
}
```
###### Example 2 - A table field ID within the range 0-49,999

```
table 50100 MyTable
{
```

#### Feedback

**Was this page helpful?**

Provide product feedback

The table field MyField has the ID 1 which is valid because it is within the range 0-

49,999.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

```
fields
{
field( 1 ; MyField; Integer) { }
}
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0003

Article•10/01/2024

Procedures must not subscribe to CompanyOpen events

Procedures must not subscribe to CompanyOpen events because it can increase the
login time for Dynamics 365 Business Central.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0061.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0004

Article•10/01/2024

Table definitions must have a matching permission set.

Table definitions must have a matching permission set.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0103.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0005

Article•10/01/2024

The compilation target of an application must be a value that is allowed in a multi-
tenant SaaS environment

The compilation target of an application must be a value that is allowed in a multi-
tenant SaaS environment.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0053.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0006

Article•10/01/2024

Encryption key functions must not be invoked.

Encryption key functions must not be invoked.

This rule validates that your extension does not invoke the following methods because
they are only supported on-premises:

```
CreateEncryptionKey
DeleteEncryptionKey
ExportEncryptionKey
ImportEncryptionKey
```
You must remove the references to the encryption key methods from your AL code.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

```
７ Note
```
```
This applies only to on-premises versions of Business Central. For online versions,
encryption is always enabled and you cannot turn it off.
```
## How to fix this diagnostic?

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0007

Article•10/01/2024

Test assertion functions are not allowed in a non-test context.

Test assertion functions are not allowed in a non-test context.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0058.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0008

Article•10/01/2024

Page controls and actions must use the ApplicationArea property

Page controls and actions must use the ApplicationArea property to be visible to users.
From runtime 11.0, you can specify on the application object level the ApplicationArea
to use as default for all its controls and actions.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0062.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

# PerTenantExtensionCop Error PTE0009

Article•10/01/2024

This app.json property must not be used for per-tenant extensions.

The properties 'helpBaseUrl' and 'supportedLocales' are reserved for translation apps.

This rule validates that the manifest of your extension (app.json) does not specify the
properties helpBaseUrl and supportedLocales. For more information, see JSON files and

Working with Translation Files.

You must remove the properties helpBaseUrl and supportedLocales from the manifest
of your extension (app.json).

The following manifest specifies the properties helpBaseUrl and supportedLocales and

is then not valid.

```
JSON
```
The following manifest does not specifies the properties helpBaseUrl and
supportLocales and is valid.

```
JSON
```
## Description

## How to fix this diagnostic?

## Code example triggering the rule

```
{
"appId": "<some-guid>",
"name": "MyApp",
"publisher": "MyPublisher",
"version": "1.0.0.0",
"helpBaseUrl": "<some-url>",
"supportedLocales": [ "en-US" ]
}
```
## Code example not triggering the rule


#### Feedback

**Was this page helpful?**

Provide product feedback

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

```
{
"appId": "<some-guid>",
"name": "MyApp",
"publisher": "MyPublisher",
"version": "1.0.0.0"
}
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0010

Article•10/01/2024

The extension name is too long.

The extension name length must not exceed the limit of 50 characters.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0047.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0011

Article•10/01/2024

The publisher name is too long.

The extension publisher length must not exceed the limit of 50 characters.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0048.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0012

Article•10/01/2024

InternalsVisibleTo should not be used as a security feature.

The InternalsVisibleTo setting will expose your internal objects to any extension with the
given name, publisher, and ID. Access modifiers are not designed to be used as a
security boundary, but for API development.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0081.

PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0013

Article•10/01/2024

Entitlements cannot be defined in an extension.

Entitlements cannot be defined in an extension because their use is restricted to
Microsoft only.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0093.

Entitlements and Permissions Sets Overview
PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0014

Article•10/01/2024

Permission Sets should not be defined in XML files.

Permission sets should not be defined in XML. Instead, use the dedicated AL object
'PermissionSet'.

For examples and guidance on fixing this diagnostic, see AppSourceCop Rule AS0094.

Entitlements and Permissions Sets Overview
PerTenantExtensionCop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0015

Article•10/01/2024

The extension name is not valid.

The extension name is not valid.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0016

Article•10/01/2024

Permission set extensions should not include permissions for objects defined in another
application.

Permission set extensions should not include permissions for objects defined in another
application. This can pose a security risk by granting excessive privileges to users.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0017

Article•10/01/2024

Permission set extensions should not include permission sets defined in another
application.

Permission set extensions should not include permission sets from another application.
This can pose a security risk by granting excessive privileges to users.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0018

Article•10/01/2024

Permission set extensions should not include permission sets which include permissions
for objects defined in another application.

Permission set extensions should not include permission sets which include permissions
for objects defined in another application. This can pose a security risk by granting
excessive privileges to users.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0019

Article•10/01/2024

Permission set extensions should not include wildcard permissions.

Permission set extensions should not include wildcard permissions. Wildcard
permissions can pose a security risk by unintentionally granting excessive privileges to
users.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0020

Article•10/01/2024

Use the 'application' property instead of specifying an explicit dependency on Base
Application.

The 'application' property should be used for expressing a dependency on the 'Base
Application'. See https://learn.microsoft.com/dynamics365/business-central/dev-
itpro/developer/devenv-application-app-file for additional information.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Error PTE0021

Article•10/01/2024

Defining reserved namespaces is not allowed.

The namespace must be different from System and Microsoft.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Warning

# PTE0022

Article•10/01/2024

The member ID should be within the allowed range

The member ID should be within the allowed range and outside the range allocated to
AppSource extensions. This warning will become an error in a future release.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PerTenantExtensionCop Info PTE0023

Article•10/01/2024

The enum ordinal value should be within the allowed range

The enum ordinal value shoul be within the allowed range and outside the range
allocated to AppSource extensions.

PerTenantExtensionCop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0001

Article•10/01/2024

The Web client does not support displaying the Request page of XMLPorts.

The Web client does not support displaying the Request page of XMLPorts.

This rule applies only to Business Central Spring 2019 and earlier versions. Request
pages for XMLPorts are supported as of Business Central 2019 release wave 2.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0002

Article•10/01/2024

The Web client does not support displaying both Actions and Fields in Cue Groups. Only
Fields will be displayed.

The Web client does not support displaying both Actions and Fields in Cue Groups. Only
Fields will be displayed.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0003

Article•10/01/2024

The Web client does not support displaying Repeater controls containing Parts.

The Web client does not support displaying Repeater controls containing Parts.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0004

Article•10/01/2024

A Blob cannot be used as a source expression for a page field.

A Blob cannot be used as a source expression for a page field.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Info AW0005

Article•10/01/2024

Actions should use the Image property.

Actions should use the Image property.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Info AW0006

Article•10/01/2024

Pages and reports should use the UsageCategory and ApplicationArea properties to be
searchable.

Pages and reports should use the UsageCategory and ApplicationArea properties to be
searchable.

For a page that should be searchable, set both the UsageCategory and ApplicationArea
properties.

If a page should not be searchable, set the property as follows:

```
AL
```
UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## How to fix this diagnostic?

```
UsageCategory = None;
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Error AW0007

Article•10/01/2024

The Web client does not support displaying Repeater controls that contain FlowFilter
fields.

The Web client does not support displaying Repeater controls that contain FlowFilter
fields.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0008

Article•10/01/2024

The Web client only supports displaying Repeater controls in pages of type List, ListPart,
and Worksheet.

The Web client only supports displaying Repeater controls in pages of type List, ListPart,
and Worksheet.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0009

Article•10/01/2024

Using a Blob with subtype Bitmap on a page field is deprecated. Instead use the
Media/MediaSet data types.

Using a Blob with subtype Bitmap on a page field is deprecated. Instead use the
Media/MediaSet data types.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0010

Article•10/01/2024

A Repeater control used on a List page must be defined at the beginning of the
area(Content) section.

A Repeater control used on a List page must be defined at the beginning of the
area(Content) section.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Info AW0011

Article•10/01/2024

Add PromotedOnly="true" to some or all promoted actions to avoid identical actions
from appearing in both the promoted and default sections of the command bar.

Add PromotedOnly="true" to some or all promoted actions to avoid identical actions
from appearing in both the promoted and default sections of the command bar.

UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0012

Article•10/01/2024

The Web client does not support properties for teaching tips in certain contexts.

The Web client does not support using properties for teaching tips in certain contexts.
Please see the property topics below for more information.

The following properties are used to enable teaching tips in the UI. For more
information, see:

```
AboutTitle Property
AboutTitleML Property
AboutText Property
AboutTextML Property
```
UICop Analyzer
Get Started with AL
Developing Extensions

## Description

## Remarks

## Related information

```
 Yes  No
```

# UICop Warning AW0013

Article•08/26/2024

Groups containing promoted actions should not be hidden.

From Business Central 2022 Wave 2, promoted actions defined in a hidden group are
rendered on the promoted side of the action bar only if the 'Modern Action Bar' feature
is disabled for the environment. If you want to always see these actions on the
promoted side, remove the Visible property on the group. If you never want to see these
actions on the promoted side, remove the Promoted property on the promoted actions.

For Business Central 2022 release wave 1 (version 20) and earlier, promoted actions
defined in a hidden group were rendered on the promoted side of the action bar, but
hidden in non-promoted side of the action bar.

From Business Central 2022 release wave 2 (version 21), promoted actions defined in a
hidden group are rendered on the promoted side of the action bar only if the 'Modern
Action Bar' feature is disabled for the environment.

The following code triggers a diagnostic from this rule because MyGroup is hidden, but

```
MyPromotedAction is Promoted.
```
```
AL
```
## Description

## Remarks

## Code example triggering the rule

```
page 50100 MyPage
{
actions
{
area(Creation)
{
group(MyGroup)
{
Visible = false;
action(MyPromotedAction)
{
Promoted = true;
```

Promoted actions are currently rendered on the promoted section of the command bar
based on the Visible property set on the action, without considering their actual visibility
in the default section of the command bar.

```
MyPromotedAction doesn't have the visible property set, so it's visible by default and the
```
promoted action will be rendered in the promoted section of the command bar.
However, since MyGroup is not visible, MyPromotedAction will also not be visible in the
default section of the command bar.

There are three ways to fix this diagnostic depending on what you want to achieve:

```
AL
```
```
}
action(MyAction)
{ } } } } }
```
```
７ Note
```
```
For versions of Business Central before 2022 release wave 2 (version 21), a similar
behavior could be achieved by using the PromotedOnly property on
MyPromotedAction. From version 21, the platform handles the duplicity of promoted
actions.
```
### How to fix this diagnostic?

###### 1. Make the action group visible

```
page 50100 MyPage
{
actions
{
area(Creation)
{
group(MyGroup)
{
action(MyPromotedAction)
{
Promoted = true;
```

There's no impact on the promoted section of the command bar as promoted actions
remain visible. However, promoted actions and non-promoted actions become visible in
the default section of the command bar.

Use this approach if you want the group and its actions to be visible.

```
AL
```
There's no impact on the promoted section of the command bar as promoted actions
remain visible. There's also no impact on the default section of the command bar since
promoted actions are promoted only and non-promoted actions remain hidden.

```
}
action(MyAction)
{ } } } } }
```
###### 2. Make the action group visible and adjust the properties

###### of actions

```
page 50100 MyPage
{
actions
{
area(Creation)
{
group(MyGroup)
{
action(MyPromotedAction)
{
Promoted = true;
PromotedOnly = true;
}
```
```
action(MyAction)
{
Visible = false;
}
}
}
}
}
```

Use this approach if you want to keep the current behaviour.

```
AL
```
There's no impact on the default section of the command bar since all actions remain
hidden by the group. However, the promoted actions do not appear in the promoted
section of the command bar anymore.

Use this approach if you didn't expect MyPromotedAction to appear in the promoted
section of the command bar and you want to hide it completely.

UICop Analyzer
Getting Started with AL
Developing Extensions

```
） Important
```
```
The behavior of the PromotedOnly property changes with Business Central 2022
release wave 2 since the platform handles the duplicity of promoted actions.
```
###### 3. Demote the actions in the group

```
page 50100 MyPage
{
actions
{
area(Creation)
{
group(MyGroup)
{
Visible = false;
action(MyPromotedAction)
{
}
action(MyAction)
{ } } } } }
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# UICop Warning AW0014

Article•10/01/2024

Groups containing ActionRef targets should not be hidden.

Actionrefs whose target actions are defined in a hidden group are still rendered on the
promoted section of the command bar, but this behavior might change and these
actionrefs might be hidden in the future. If you want to see these actions in the default
section of the command bar, remove the Visible property on the group. If you do not
want to see these actions on the promoted section of the command bar, remove the
actionrefs.

The following code triggers a diagnostic from this rule because MyGroup is hidden, but

```
MyPromotedAction is the target of an ActionRef.
```
```
AL
```
## Description

## Code example triggering the rule

```
page 50100 MyPage
{
actions
{
area(Promoted)
{
actionref(MyActionRef; MyPromotedAction)
{
}
}
area(Creation)
{
group(MyGroup)
{
Visible = false;
```
```
action(MyPromotedAction)
{ } } } } }
```

The visibility of actionrefs depends on the visibility of their target actions. If the target
action's Visible property is set to false, then the actionref is hidden too.

However, actionrefs actions are currently rendered on the promoted section of the
command bar based on the Visible property set on the action and the actionref, without
considering the actual visibility of their target action in the default section of the
command bar.

```
MyPromotedAction doesn't have the visible property set, so it's visible by default and the
```
promoted action will be rendered in the promoted section of the command bar.
However, since MyGroup isn't visible, MyPromotedAction will also not be visible in the
default section of the command bar.

There are three ways to fix this diagnostic depending on what you want to achieve:

```
AL
```
```
７ Note
```
```
You can achieve a similar behavior by using the PromotedOnly property on
MyPromotedAction.
```
### How to fix this diagnostic?

###### 1. Make the action group visible

```
page 50100 MyPage
{
actions
{
area(Promoted)
{
actionref(MyActionRef; MyPromotedAction)
{
}
}
area(Creation)
{
group(MyGroup)
{
action(MyPromotedAction)
{
}
}
}
```

There's no impact on the promoted section of the command bar as the actionref
remains visible. However, promoted actions and non-promoted actions become visible
in the default section of the command bar.

Use this approach if you want the group and its actions to be visible.

```
AL
```
There's no impact on the default section of the command bar since all actions remain
hidden by the group. However, the actionref no longer appears in the promoted section
of the command bar. Use this approach if you didn't expect MyPromotedAction to appear

in the promoted section of the command bar and you want to hide it completely.

Remark, in order to be compliant with the breaking change validation from the
AppSourceCop, the following change is recommended:

```
AL
```
```
}
}
```
###### 2. Remove the actionrefs for the actions in the group

```
page 50100 MyPage
{
actions
{
area(Creation)
{
Visible = false;
group(MyGroup)
{
action(MyPromotedAction)
{ } } } } }
```
```
page 50100 MyPage
{
actions
{
area(Promoted)
{
actionref(MyActionRef; MyPromotedAction)
```

#### Feedback

**Was this page helpful?**

Provide product feedback

UICop Analyzer
Getting Started with AL
Developing Extensions

```
{
Visible = false;
ObsoleteState = Pending;
ObsoleteReason = 'Will be removed in a future version';
}
}
area(Creation)
{
Visible = false;
group(MyGroup)
{
action(MyPromotedAction)
{ } } } } }
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0015

Article•10/01/2024

Actions with scope repeater must be promoted.

Actions with scope repeater must be promoted in order to appear on the repeater
control.

UICop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# UICop Warning AW0016

Article•10/01/2024

Rich Text Editor fields are only allowed while alone in a FastTab group.

The Rich Text Editor field must reside alone within a FastTab group.

UICop Analyzer
Getting Started with AL
Developing Extensions

## Description

## Related information

```
 Yes  No
```

# Data types and methods in AL

Article•08/26/2024

The following data types are available as part of the AL language. Each data type has
various methods that support it. For more information about a data type and its
methods, select a link in the table.

```
Type Description
```
```
Any This data type can be substituted by any other data type.
BigInteger Stores very large whole numbers that range from
-9,223,372,036,854,775,807 to 9,223,372,036,854,775,807.
```
```
BigText Handles large text documents.
Blob Is a complex data type. Variables of this data type differ from
normal numeric and string variables in that BLOBs have a
variable length. The maximum size of a BLOB(binary large
object) is 2 GB.
```
```
Boolean Indicates true or false.
Byte Stores a single, 8-bit character as a value in the range 0 to 255.
You can easily convert this data type from a number to a
character and vice versa. This means you can use mathematical
operators on Byte variables.
Char Stores a single, 16-bit character as a value in the range 0 to
```
65535. You can convert this data type from a number to a
character and vice versa. This means you can use mathematical
operators on Char variables.

```
Code Denotes a special type of string that is converted to uppercase
and removes any trailing or leading spaces.
Codeunit Is a container for AL code that you can use from other
application objects.
CompanyProperty Provides language support for company properties.
```
```
Cookie Provides a data structure to work with Http cookies.
Database Provides access to common database functionality.
```
```
DataTransfer A structure building bulk transfer of data between tables.
```
```
ﾉ Expand table
```

**Type Description**

Date Denotes a date ranging from January 1, 1753 to December 31,
9999.

DateFormula Represents a date formula that has the same capabilities as an
ordinary input string for the CALCDATE Method (Date). The
DateFormula data type is used to provide multilanguage
capabilities to the CALCDATE Method (Date).

DateTime Denotes a date and time ranging from January 1, 1753,
00:00:00.000 to December 31, 9999, 23:59:59.999. An undefined
or blank DateTime is specified by 0DT.

Debugger Enables communication with a debugger.

Decimal Denotes decimal numbers ranging from
-999,999,999,999,999.99 to +999,999,999,999,999.99.

Dialog Represents a dialog window.

Dictionary Represents an unordered collection of keys and values. The
Dictionary data type is optimized for fast lookup of values.

DotNet Represents an unspecified .NET type.

Duration Represents the difference between two DateTimes. This value
can be negative. It is stored as a 64-bit integer. The integer value
is the number of milliseconds during the duration.

Enum Represents the text content of an element or attribute.

ErrorInfo Provides a structure for grouping information about an error.

FieldRef Identifies a field in a table and gives you access to this field.

File Represents a file.

FileUpload Represents a file.

FilterPageBuilder Stores filter configurations for a filter page. A filter page is a
dynamic page type that contains one or more filter controls that
enables users to set filters on fields of the underlying tables.

Guid Represents a 16 byte binary data type. This data type is used for
the global identification of objects, programs, records, and so
on. The important property of a GUID is that each value is
globally unique. The value is generated by an algorithm,
developed by Microsoft, which assures this uniqueness.

HttpClient Provides a data type for sending HTTP requests and receiving
HTTP responses from a resource identified by a URI.


**Type Description**

HttpContent Represents an HTTP entity body and content headers.

HttpHeaders Is a collection of headers and their values.

HttpRequestMessage Represents an HTTP request message.

HttpResponseMessage Represents an HTTP response message including the status
code and data.

InStream Is a generic stream object that you can use to read from or write
to files and BLOBs. You can define the internal structure of a
stream as a flat stream of bytes. You can assign one stream to
another. Reading from and writing to a stream occurs
sequentially.

Integer Stores whole numbers with values that range from
-2,147,483,647 to 2,147,483,647.

IsolatedStorage Provides data isolation for extensions.

JsonArray Is a container for any well-formed JSON array. A default
JsonArray contains an empty JSON array.

JsonObject Is a container for any well-formed JSON object. A default
JsonObject contains an empty JSON object.

JsonToken Is a container for any well-formed JSON data. A default
JsonToken object contains the JSON value of NULL.

JsonValue Is a container for any well-formed fundamental JSON value. A
default JsonValue is set to the JSON value of NULL.

KeyRef Identifies a key in a table and the fields in this key.

Label Denotes a string constant that can be optionally translated into
multiple languages.

List Represents a strongly typed list of ordered objects that can be
accessed by index. Contrary to the Array data type, a List is
unbounded, such that its dimension does not need to be
specified upon declaration.

Media Encapsulates media files, such as image .jpg and .png files, in
application database tables. The Media data type can be used as
a table field data type, but cannot be used as a variable or
parameter. The Media data type enables you to import a media
file to the application database and reference the file from
records, making it possible to display the media file in the client
user interface. You can also export media from the database to
files and streams.


**Type Description**

MediaSet Encapsulates media, such as images, in application database
tables.

ModuleDependencyInfo Provides information about a dependent module.

ModuleInfo Represents information about an application consumable from
AL.

NavApp Provides information about a NavApp.

None Is used implicitly when a method does not return a value.

Notification Provides a programmatic way to send non-intrusive information
to the user interface (UI) in the Business Central Web client.

NumberSequence Is a complex data type for creating and managing number
sequences in the database.

Option Denotes an option value. In the code snippet below, you can see
how the Option data type is declared.

OutStream Is a generic stream object that you can use to write to files and
BLOBs.

Page Contains a number of simpler elements called controls. Controls
are used to display information to the user or receive
information from the user.

ProductName An application can have a full name, marketing name, and short
name. The PRODUCTNAME functions enable you to retrieve
these name variations.

Query Enables you to retrieve data from multiple tables and combine
the data in single dataset.

Record Is a complex data type.

RecordId Contains the table number and the primary key of a table.

RecordRef References a record in a table.

Report Is used to display, print, or process information from a database.

RequestPage Is a page that is run before the report starts to execute. Request
pages enable end-users to specify options and filters for a
report.

SecretText Denotes a secret text string, which is non-debuggable.

Session Represents a Microsoft Dynamics Business Central session.


**Type Description**

SessionInformation Is a complex data type for exposing Session information into AL.

SessionSettings Is a complex data type for passing user personalization settings
for a client session as an object. The object contains properties
that correspond to the fields in the system table **2000000073
User Personalization** , including: App ID, Company, Language ID,
Locale ID, Profile ID, Scope, and Time Zone. You can use the AL
methods of the SessionSettings data type to get, set, and send
the user personalization settings for the current client session.

System Is a complex data type.

TaskScheduler TaskScheduler is a complex data type used for creating and
managing tasks in the task scheduler, which runs codeunits at
scheduled times.

TestAction Represents a test action on a page.

TestField Represents a testable field on a page.

TestFilter Represents a test filter on a page.

TestFilterField Represents the type of a field filter in a test filter on a page or
on a request page.

TestPage Represents a variable type that can be used to test Page
Application Objects.

TestPart Represents a variable type that can be used to test Page
Application Objects of type Part.

TestRequestPage Stores test request pages. A test request page part is a logical
representation of a request page on a report. A test request
page does not display a user interface (UI). The subtype of a test
request page is the report whose request page you want to test.

Text Denotes a text string.

TextBuilder Represents a lighweight wrapper for the .Net implementation of
StringBuilder.

TextConst Denotes a multi-language string constant.

Time Denotes a time ranging from 00:00:00.000 to 23:59:59.999. An
undefined or blank time is specified by 0T.

Variant Represents an AL variable object. The AL variant data type can
contain many AL data types.


**Type Description**

Version Represents a version matching the format:
Major.Minor.Build.Revision.

WebServiceActionContext Represents an AL WebServiceActionContext.

XmlAttribute Represents an XML attribute.

XmlAttributeCollection Represents a collection of XML attributes.

XmlCData Represents a CData section.

XmlComment Represents an XML comment.

XmlDeclaration Represents an XML declaration.

XmlDocument Represents an XML document.

XmlDocumentType Represents an XML document type.

XmlElement Represents an XML element.

XmlNamespaceManager Represents a namespace manager that can be used to resolve,
add and remove namespaces to a collection. It also provides
scope management for these namespaces.

XmlNameTable Represents a table of atomized string objects.

XmlNode Represents a XML node which can either be for instance an XML
attribute, an XML element or a XML document.

XmlNodeList Represents a collection of XML nodes.

Xmlport XmlPorts are used to export or import data between an external
source and a Microsoft Dynamics Business Central database.

XmlProcessingInstruction Represents a processing instruction, which XML defines to keep
processor-specific information in the text of the document.

XmlReadOptions Represents the options configuring how XML is loaded from a
data source.

XmlText Represents the text content of an element or attribute.

XmlWriteOptions Represents the options configuring how XML is saved.

Action Represents the action that the user took on the page.

AuditCategory Represents an audit category for IfX audit telemetry.

ClientType Represents the type of the client executing the operation.


**Type Description**

CommitBehavior Specifies whether commit is allowed within the scope of the
method.

DataClassification Sets the classification of the data in the table or field.

DataScope Identifies the scope of stored data in the isolated storage.

DefaultLayout The default layout to be used by a report.

ErrorBehavior Specifies whether errors will be collected within the scope of the
method.

ErrorType Represents the type of error.

ExecutionContext Represents the context in which a session is running. In certain
scenarios, for example during upgrade, the system will run a
session in a special context for a limited time.

ExecutionMode The execution mode of the current session.

FieldClass Represents the type of a field class.

FieldType Represents the type of a table field.

InherentPermissionsScope The different types of scope that the InherentPermissions
attribute can apply to.

IsolationLevel The isolation level applied for this record.

NotificationScope Specifies the context in which the notification appears in the
client.

ObjectType The different types of objects.

PageBackgroundTaskErrorLevel Specifies how an error in the page background task appears in
the client.

PageStyle Represents the different kinds of styles that can be applied to
page controls.

PermissionObjectType The different types of objects that can have different
permissions assigned.

PromptMode Specifies the current mode of a PromptDialog page.

ReportFormat Specifies the format of the report.

ReportLayoutType Represents the type of a report layout.

SecurityFilter Specifies how security filters are applied to the record.


#### Feedback

**Was this page helpful?**

Provide product feedback

```
Type Description
SecurityOperationResult Represents security audit operation result.
```
```
TableConnectionType Use variables of this data type to specify the type of connection
to an external database.
TelemetryScope Represents the emission scope of the telemetry signal.
```
```
TestPermissions Specifies a value that can be used to determine which
permission sets are used on tests that are run by test codunits
or test functions.
```
```
TextEncoding Represents a file encoding.
TransactionModel Represents a test transaction model.
```
```
TransactionType Represents a transaction type.
Verbosity Represents the security level of events.
```
```
WebServiceActionResultCode Represents a web service action status code.
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# Array methods

Article•03/19/2024

An array is a data structure that contains many variables, which are accessed through
computed indices. An index is the location of the variable stored in an array. The
variables contained in an array are also called the elements of the array. The array
always stores elements of the same data type.

An array has a rank that determines the number of indices that is how long it takes to
reach an element. And if there are repeating elements, their rank is same as their first
occurrence in the array. The rank of an array is also referred to as the dimension of the
array. An array with a rank of one is called a single-dimensional array. An array with a
rank greater than one is called a multi-dimensional array. Specific sized multi-
dimensional arrays are often referred to as two-dimensional arrays, three-dimensional
arrays, and so on. Each dimension of an array has an associated length, which is an
integral number greater than or equal to zero. The maximum number of dimensions is
10 and the total number of elements in all dimensions is 1,000,000.

The length of a dimension determines the valid range of indices for that dimension. For
a dimension of length N, indices can range from **1 to N** inclusive. The total number of
elements in an array is the product of the lengths of each dimension in the array. If one
or more of the dimensions of an array have a length of zero, the array is considered to
be empty.

The syntax for declaring an array of a specific type is the following:

```
AL
```
The Dimension is a comma-delimited list of integer literals greater than 0, where each

integer defines the number of elements in that dimension.

The Type is the element type of the array.

## Syntax

```
array [Dimension] of Type;
```
## Code example


The following code sample shows the declaration of an array with a simple element
type.

```
AL
```
The following code sample shows the declaration of an array with an element type of a
fixed length.

```
AL
```
The following code sample shows the declaration of an array with a complex element
type.

```
AL
```
The following AL methods for arrays are available:

ArrayLen method
CompressArray method
CopyArray method

The following code sample shows the declaration of an array of temporary Item records:

```
AL
```
```
arrayOfInteger: array [ 10 ] of Integer;
```
```
arrayOfCode: array [ 10 ] of Code[ 20 ];
arrayOfText: array [ 10 ] of Text[ 20 ];
```
```
arrayOfCodeunits: array [ 10 ] of Codeunit 10 ;
arrayOfQueryes: array [ 10 ] of Query "My Query";
arrayOfTemporaryRecords: array [ 10 ] of Record 10 Temporary;
arrayOfDotNetVariables: array [10] of DotNet String;
```
### Methods

### Array of temporary records

```
itemRecArrayTemp: array[ 2 ] of Record Item temporary;
```

#### Feedback

**Was this page helpful?**

Provide product feedback

In this case, each element of the array contains a temporary Item record referencing the
same temporary table, meaning that an insert into itemRecArrayTemp[0] is also reflected
in itemRecArrayTemp[1].

This is the same behavior as using Copy(RecordRef [, Boolean]) with the ShareTable
parameter set to true.

AL Method Reference

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Essential AL methods

Article•11/25/2024

Although there are hundreds of methods in AL, there are several methods that you use
more often than the others. It doesn't mean that the rest of the methods are obsolete or
that you never use them. However, it does mean that if you're familiar with this small set
of essential methods, you are able to accomplish many tasks when you're programming
in AL. When you want to add more specialized functionality to your applications, you
can learn about more of the methods.

The articles in this section describe the most common AL methods. For more
information about all of the AL methods, see AL method reference.

```
Get, Find, and Next methods
SetCurrentKey, SetRange, SetFilter, GetRangeMin, and GetRangeMax methods
Insert, Modify, ModifyAll, Delete, and DeleteAll methods
LockTable method
Field Calculation methods
Progress Windows, Message, Error, and Confirm methods
StrMenu method
```
AL method reference

## Related information

```
 Yes  No
```

# Get, Find, and Next methods

Article•04/17/2024

The following methods are used to search for records:

```
Get
Find
Next
```
These methods are some of the most frequently used AL methods. When you search for
records, you must know the difference between Get and Find. You should also know

how to use Find and Next in conjunction.

The Get method (Record) retrieves one record based on values of the primary key fields.

```
Get has the following syntax.
```
```
AL
```
For example, if the **No.** field is the primary key of the **Customer** table and if you've
created a record variable called **CustomerRec** that has a subtype of Customer, then you
can use Get in the following way.

```
AL
```
The result is that the record of customer 4711 is retrieved.

```
 Tip
```
```
When using these methods, consider using the partial records methods to improve
performance, especially when looping through several records or when table
extensions are defined on the table. For more information, see Using partial
records.
```
## Get method

```
[Ok :=] Record.Get([Value],...)
```
```
CustomerRec.Get('4711');
```

Get produces a runtime error if it fails and the return value isn't checked by the code. In
the previous example, the actual code that you write should resemble the following.

```
AL
```
Get searches for a record without changing any current filters. Get always searches
through all the records in a table.

```
APPLIES TO: Business Central 2019 release wave 2 and later
```
The GetBySystemId(Guid) retrieves a record based on the value of its **SystemId** field.

```
GetBySystemId has the following syntax:
```
```
AL
```
The following example gets the record that has the SystemId 5286305A-08A3-E911-8180-
001DD8B7338E:

```
AL
```
Similar to the Get method, GetBySystemId also searches for a record without changing

any current filters.

```
if CustomerRec.GET('4711') then
.... // Do some processing.
else
.... // Do some error processing.
```
### GetBySystemId method

```
RecordExists := Record.GetBySystemId(SystemId: Guid)
```
```
var
Customer: Record Customer;
Text000: Label 'Customer was found.';
begin
If Customer.GetBySystemId('{5286305A-08A3-E911-8180-001DD8B7338E}') then
Message(Text000);
end;
```
### Find methods


The Find method (Record) locates a record in a table that is based on the values stored
in the keys.

```
Find has the following syntax.
```
```
AL
```
The _Which_ parameter specifies how to perform the search. You can search for values
that are greater than, less than, or equal to the key value, or for the first or last record in
a table.

The important differences between Get and Find are as follows:

```
Find uses the current filters.
```
```
Find can look for records where the key value is equal to, greater than, or smaller
than the search string.
```
```
Find can find the first or the last record, depending on the sort order defined by
the current key.
```
When you're developing applications in a relational database, there are often one-to-
many relationships defined between tables. An example could be the relationship
between an **Item** table, which registers items, and a **Sales Line** table, which registers the
detailed lines from sales orders. One record in the **Sales Line** table can only be related
to one item, but each item can be related to any number of sales line records. You won't
want an item record to be deleted as long as there are still open sales orders that
include the item. You can use Find to check for open sales orders.

If you want to find the first record in a table or set, then use the FindFirst method
(Record). If you want to find the last record in a table or set, then use the FindLast
method (Record).

The PickItem procedure of the **Item** table includes the following code that illustrates
using FindFirst.

```
AL
```
```
Ok := Record.Find([Which])
```
```
procedure PickItem(var Item: Record Item): Code[ 20 ]
var
ItemList: Page "Item List";
begin
if Item.FilterGroup = - 1 then
```

#### Feedback

The Next method (Record) is often used with FIND to step through the records of a
table.

```
Next has the following syntax.
```
```
AL
```
In the following example, Find is used to go to the first record of the table. Next is used

to step through every record, until there are no more. When there are no more records,
Next returns a 0 (zero).

```
AL
```
AL methods
SystemId field

```
ItemList.SetTempFilteredItemRec(Item);
if Item.FindFirst() then;
ItemList.SetTableView(Item);
ItemList.SetRecord(Item);
ItemList.LookupMode := true;
if ItemList.RunModal() = ACTION::LookupOK then
ItemList.GetRecord(Item)
else
Clear(Item);
```
```
exit(Item."No.");
end;
```
### Next method

```
Steps := Record.Next([Steps])
```
```
if (Rec.FindSet) then
repeat
// process record
until (Rec.Next = 0 );
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# Create Handler Methods

Article•08/16/2022

You can create test codeunits, test methods, and test pages to test your application. We
recommend that you create tests that can be automated. To create automated tests, you
must write code to handle all UI interactions so that the tests don't require user
interaction when they're running. To do this, you create special handler methods.

You can use the following handler methods:

```
Method type Purpose Signature
MessageHandler Handles Message statements. < Function name >
(< Message >: Text[1024])
```
```
ConfirmHandler Handles Confirm statements. < Function name >
(< Question >: Text[1024];
var < Reply >: Boolean)
StrMenuHandler Handles StrMenu statements. < Function name >
(< Options : Text[1024];
var < Choice >: Integer;
<Instruction>:
Text[1024])
```
```
PageHandler Handles specific pages that aren't run
modally.
```
```
< Function name >(var
<Page>: Page < page
id >)
```
```
< Function name >(var
<Page>: TestPage
< testpage id >)
```
```
ModalPageHandler Handles specific pages that are run
modally.
```
```
< Function name >(var
<Page>: Page < page
id >; var <Response>:
Action)
```
```
< Function name >(var
<Page>: Page < testpage
id >)
ReportHandler Handles specific reports. If you create a
ReportHandler method, then that method
```
```
< Function name >(var
<Report>: Report
```
```
ﾉ Expand table
```

```
Method type Purpose Signature
replaces all code for running the report,
including the request page, and a
RequestPageHandler isn't called. Only
create a RequestPageHandler if you aren't
using a ReportHandler.
```
```
< report id >)
```
```
FilterPageHandler Handles a specific filter page. The
FilterPageHandler tests the UI that is
generated by a FilterPageBuilder Data
Type.
```
```
< Function name >(var
<Record1>: RecordRef)[,
var <Record2>:
RecordRef] [, ...]):
Boolean
RequestPageHandler Handles the request page of a specific
report.
```
```
< Function name >(var
<RequestPage>:
TestRequestPage)
HyperlinkHandler Handles specific hyperlinks. < Function name >
(<Hyperlink>:
Text[1024])
SendNotificationHandler Handles Send statements. < Function name >
(< TheNotification >:
Notification): Boolean
RecallNotificationHandler Handles Recall statements. < Function name >
(< TheNotification >:
Notification): Boolean
SessionSettingsHandler Handles RequestSessionUpdate
statements.
```
```
< Function name >(var
< SessionSettings >:
SessionSettings):
Boolean
```
To create a handler method, you set one of the handler attributes on a method. You
must use the method signature specified for the handler attribute that you're using, as
illustrated in this code example.

```
AL
```
### How to create a handler method

```
[MessageHandler]
procedure MessageHandler(Message: Text[ 1024 ])
begin
Assert.IsTrue(StrPos(Message, MSG_HAS_BEEN_CREATED) > 0 , Message);
end;
```

#### Feedback

The parameters of the methods that are being handled are passed as parameters to the
handler methods. For example, when **Message** is called in a test method, the parameter
of the **Message** method is passed as the parameter of the **MessageHandler** method. For
page and report handlers, the page, report, or request page is passed as the parameter
of the **PageHandler** , **ModalPageHandler** , **ReportHandler** , or **RequestPageHandler**.

You can call handler methods from methods that have the Test Attribute and then
specify the handler methods that it will use in the HandlerFunctions Attribute. The code
inside the test method should simulate that the UI was actually raised and some values
entered or some actions were taken. You can specify more than one handler method by
separating the handler method names with a comma.

The following example shows a test method that uses the HandlerFunctions Attribute to
call the **MessageHandler** method.

```
AL
```
Testing the Application
AL Methods

```
７ Note
```
```
Every handler method that you enter in the HandlerFunctions Attribute of a test
method must be called at least one time in the test method. If you run a test
method that has a handler method listed that isn't called, then the test fails.
```
```
[Test]
[HandlerFunctions('MessageHandler')]
procedure ApproveRequestForPurchCreditMemo()
var
PurchHeader: Record "Purchase Header";
begin
ApproveRequestForPurchDocument(PurchHeader."Document Type"::"Credit
Memo");
end;
```
### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# Handling errors using try methods

Article•11/14/2024

Try methods in AL enable you to handle errors that occur in the application during code
execution. For example, with try methods, you can provide more user-friendly error
messages to the end user than errors thrown by the system.

The main purpose of try methods is to catch errors/exceptions thrown by the Business
Central AL platform. For on-premises, they can catch exceptions thrown during .NET
Framework interoperability operations. Try methods catch errors similar to a conditional
Codeunit. Except for the try method, the Run method call doesn't require that write
transactions are committed to the database, and changes to the database that are made
with a try method aren't rolled back.

Because changes made to the database by a try method aren't rolled back, you
shouldn't include database write transactions within a try method. For Business Central
online, there are no restrictions on performing write transactions in try methods. For
Business Central on-premises, the Business Central Server prevents database write
transactions within try methods by default. If a try method contains a database write
transaction, a runtime error occurs. You can allow write transactions by setting the
DisableWriteInsideTryFunctions parameter in the Business Central Server configuration

to false. Learn more about configuring the server in Configure Business Central Server.
This behavior might change in an upcoming release.

A method that is designated as a try method has a Boolean return value ( **true** or **false** ),
and has the construction OK:= MyTrymethod. A try method can't have a user-defined

return value.

```
７ Note
```
```
Try Methods are available from runtime version 2.0.
```
## Behavior and usage

## Database write transactions in try methods

## Handling errors with a return value


```
If a try method call doesn't use the return value, the try method operates like an
ordinary method, and errors are exposed as usual.
If a try method call uses the return value in an OK:= statement or a conditional
statement such as if-then, errors are caught. The try method returns true if no
error occurs; false if an error occurs.
```
You can use the GetLastErrorText method to obtain errors generated by Business
Central. To get details of exceptions generated by the AL platform or by .NET objects,
you can use the GetLastErrorObject method to inspect the Exception.InnerException

property.

To create a try method, add a method in the AL code of an object such as a codeunit,
and then set the TryFunction Attribute.

The following simple example illustrates how the try method works. First, create a
codeunit that has a local method MyTrymethod. Add the following code on the OnRun

trigger and MyTrymethod method.

```
AL
```
```
AL
```
```
７ Note
```
```
The return value isn't accessible within the try method itself.
```
###### Getting details about errors

### Creating a try method

### Example

```
trigger OnRun()
begin
MyTrymethod;
message('Everything went well');
end;
```
```
local procedure MyTryMethod()
begin
```

#### Feedback

**Was this page helpful?**

Provide product feedback

When you run this codeunit, the execution of the OnRun trigger stops. The error

message An error occurred during the operation is thrown in the UI.

Now, set the TryFunction Attribute of the MyTrymethod method. Then, add code to the
OnRun trigger to handle the return value of the try method:

```
AL
```
When you run the codeunit, instead of stopping the execution of the OnRun trigger

when the error occurs, the error is caught, and the message Something went wrong is

returned.

Failure modeling and robust coding practices
AL error handling
AL Simple Statements

```
error('An error occurred during the operation');
end;
```
```
[TryFunction]
local procedure MyTryMethod()
begin
error('An error occurred during the operation');
end;
```
```
trigger OnRun()
begin
if MyTryMethod then
message('Everything went well')
else
message('Something went wrong')
end;
```
### Related information

```
 Yes  No
```

# Collectible errors API

Article•01/04/2024

AL includes several methods, properties, and attributes that are designed specifically for
the collectable errors feature. For more information, see Collecting Errors.

The following methods are available on the ErrorInfo data type for defining information
about errors. These methods can be invoked using property access syntax.

```
Method Description
ErrorInfo.Create(String [, Boolean] [, var Record] [, Integer] [,
Integer] [, String] [, Verbosity] [, DataClassification] [, Dictionary
of [Text, Text]])
```
```
Creates a new ErrorInfo object.
```
```
ErrorInfo.Callstack() Specifies a callstack where the
ErrorInfo was collected.
ErrorInfo.Collectible([Boolean]) Specifies whether the error is
collectible using
ErrorBehavior.Collect.
ErrorInfo.CustomDimensions([Dictionary of [Text, Text]]) Set of dimensions, specified as a
dictionary that relates to the
error.
ErrorInfo.FieldNo([Integer]) Specifies the field ID that the
error relates to.
```
```
ErrorInfo.PageNo([Integer]) Specifies the page number that
the error relates to.
```
```
ErrorInfo.RecordId([RecordId]) Specifies the record ID of the
record that the error relates to.
ErrorInfo.SystemId([Guid]) Specifies the system ID of the
record that the error relates to.
ErrorInfo.TableId([Integer]) Specifies the table ID that the
error relates to.
```
## Error information methods

```
ﾉ Expand table
```

#### Feedback

The following methods are available on the System data type for handling collected
errors. These methods can be invoked using property access syntax.

```
Method Description
System.HasCollectedErrors() Gets a value indicating whether errors have been collected
in the current error collection scope.
```
```
System.GetCollectedErrors([Boolean]) Gets all collected errors in the current collection scope.
System.ClearCollectedErrors() Clears all collected errors from the current collection
scope.
```
The ErrorBehavior specifies the behavior of collectable errors inside the method scope.
Adding [ErrorBehavior(ErrorBehavior.Collect)] to a procedure makes it possible to

collect and handle errors that are raised in the scope of the procedure.

ErrorInfo data type
ErrorBehavior attribute
Collecting Errors
AL Simple Statements

### Collected errors

```
ﾉ Expand table
```
```
） Important
```
```
If you clear the list of collected errors, any changes performed in the database
won't be rolled back. So, in most cases, it makes sense to combine the clear
operation with an if Codeunit.Run then ... statement, as shown in the
PostWithErrorCollectCustomUI procedure of the example.
```
### Error behavior

### Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# Progress Windows, Message, Error, and

# Confirm Methods

Article•12/22/2023

You can use several specialized methods to display messages and gather input. We
recommend that you use pages to ensure that your application has a consistent user
interface. However, there are situations where you may want to use the dialog methods
instead of pages. The most important uses of the dialog methods are as follows:

```
To display a window that indicates the progress of some processing that may take
a long time.
```
```
To stop the running program to display an error message.
```
```
To let the user confirm a choice before the program continues running.
```
You can also use the StrMenu method to create pages that present options to the user.
It's much faster to use this method than to design a page, which only presents a limited
set of options to the user. For more information about the StrMenu method, see
StrMenu Method.

We recommend the following guidelines for writing messages for end users:

```
Write messages correctly according to the grammatical rules for your language.
```
```
Don't use backslashes to indicate line breaks in a message. Line formatting is
completed automatically. The only exception is in the Open Method). You must use
backslashes for the message to be aligned correctly.
```
```
Use the FieldCaption Method) and TableCaption Method) whenever possible to
return names of fields and tables as strings. It's so that the user can always
recognize a term that indicates a field or table name. The only exception to this is
in Open Method) where you can use the field name directly. Otherwise, it can be
difficult to align correctly. If you refer to a field name without using the
FieldCaption method, then type the field name without any single or double
quotation marks.
```
```
Try to write all messages on only one line. If you want to use more than one line,
then start a new line after a period instead of in the middle of a sentence.
```
## Best practices for user messages


```
Don't enter the text directly in the AL code. Instead, enter it as a label so that the
message can be translated.
```
If you have an application whose processing can take a long time to complete, then you
should consider displaying a window that informs the user of the progress that is being
made. It's always a good idea to inform the user that processes are still running.

A **Cancel** button is automatically added to every dialog window and gives user the
opportunity to stop the processing.

In some applications, you may want to create a window in which each field is updated
when the program is running. For example, the fields in the window, display the count of
the postings made. In another application, you may want to display information about
the record that is currently being processed. For example, the field in the window,
displays the number of the account that is currently being processed.

To create this kind of progress window, you use the Dialog data type.

The Message Method) displays a message in a window that remains open until the user
chooses the **OK** button.

The Message method has the following syntax.

```
AL
```
The Message method runs asynchronously, which means that the message isn't run until
the method from which it was called ends or another method requests user input. The
method is useful for notifying the user that some processing has been successfully
completed.

For an example of the Message method, see codeunit 83 in the CRONUS International
Ltd. demonstration database. The code in the OnRun trigger converts a quote into a
sales order and then displays a message. The message is generated by the following
code.

```
AL
```
### Creating a window to indicate progress

### Message method

```
message(String [, Value1, ...]);
```

The Error Method is similar to the Message method except that when the user has
acknowledged the message from an Error method, AL execution ends. The Error

method is also similar to the FieldError method. For more information on the FieldError

method, see CalcFields, CalcSums, FieldError, FieldName, Init, TestField, and Validate
Methods.

The Error method has the following syntax:

```
AL
```
For more information about error handling in AL, see Error handling overview.

```
var
Text001 : Label 'Quote %1 has been changed to order %2';
message(Text001,"No.",SalesHeader2."No.");
```
```
７ Note
```
```
Unlike the progress window, the Message method doesn't require that you first
declare a variable of the type Dialog. The Message method creates a window of its
own.
```
### Error method

```
procedure MyProc()
var
MyErrorInfo: ErrorInfo;
begin
// setup ErrorInfo
MyErrorInfo.Title('Error message title that the user sees.');
MyErrorInfo.Message('Error message the user sees.');
MyErrorInfo.DetailedMessage('(Hidden) error details for the person who
needs to troubleshoot.');
// add more properties for ErrorInfo depending on the scenario
Error(MyErrorInfo);
```
```
// no more AL code runs after the Error method
end;
```
### Confirm method


#### Feedback

**Was this page helpful?**

Provide product feedback

The Confirm Method) is used just like the Message method to display a message.

However, unlike the Message method, the Confirm method has a required return value.

The Confirm method has the following syntax.

```
AL
```
The following example shows how to use the Confirm method.

```
AL
```
The false parameter in the confirm statement means that No is the default.

Error handling overview
Dialog data type

```
Ok := Dialog.Confirm(String [, Default] [, Value1] ,...);
```
```
if confirm('Do you want to post the journal lines and print report %1?',
False, ReportID) then
message('Posting')
else begin
message('No Posting');
exit;
end;
```
### Related information

```
 Yes  No
```

# Create Test Codeunits and Test Methods

Article•08/16/2022

In Dynamics 365 Business Central, you can create test codeunits and then test methods
in the test codeunits.

Test codeunits are codeunits that have the SubType Property set to **Test**. You write tests
as AL code in the methods inside of the test codeunits. There are three types of
methods that you can add in a test codeunit: test, handler, and normal. Each method
type is used for a specific purpose and behaves differently. When a test codeunit runs, it
runs the **OnRun** trigger, and then runs each test method in the codeunit.

By default, each test method runs in a separate database transaction, but you can use
the TransactionModel Attribute on test methods and the TestIsolation Property on test
runner codeunits to control the transactional behavior.

The results of a test codeunit and of the individual test methods are displayed in a
message window, but you can use the OnAfterTestRun Trigger on a test runner codeunit
to capture the results. The outcome of a test method is either SUCCESS or FAILURE. If
any error is raised by either the code that is being tested or the test code, then the
global outcome of the test codeunit is FAILURE and the error is included in the results
log file.

The difference between a normal codeunit and a test codeunit is their execution at
runtime. When a normal codeunit is run, if one of its methods fails, then the codeunit is
terminated. When a test codeunit is run, even if the outcome of one test method is
FAILURE, the next test methods are still running.

The methods in a test codeunit can be one of the following types:

```
Type Description
```
```
Test
method
```
```
You use test methods that include AL code that tests the business logic in the
application, where each method covers a transaction. You declare the Test Attribute on
the method.
```
```
Handler
method
```
```
You use handler methods to automate tests by handling instances when user
interaction is required by the code that is being tested by the test method. In these
instances, the handler method is run instead of the requested user interface. The
handler method should simulate the user interaction for the test case, such as
validating messages, making selections, or entering values. You declare a handler type
attribute on the method. For more information, see Create Handler Methods
```
```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Type Description
Normal
method
```
```
You use normal methods to structure the test code by using the same design practices
and principles as methods in other codeunits of the application. You declare the
Normal Attribute on the method.
```
Testing the Application

### Related information

```
 Yes  No
```

# Procedure overload

Article•11/25/2024

Procedure overload enables developers to create multiple procedures with the same
name, but with different signatures, on the same application object. Conceptually,
overloaded procedures are used to execute the same task on a different set of
arguments. When an overloaded procedure is called, a specific implementation of that
procedure, appropriate to the context of the call, will be run.

Overloaded procedures give programmers the flexibility to call a procedure with similar
semantics for different types of data. At the same time, overloaded procedures remove
the need for abusing the Variant data type for the purpose of processing different types
of data in a similar manner and allows the developer to write strongly-typed code and
rely on the compiler for validation.

Overload resolution is performed by using procedure signatures to find the best match.
The signature of a procedure is represented by its name and the type, order, and
number of parameters. The return type of a procedure is not part of the procedure’s
signature.

The following example shows how a **ToString** method can be implemented with and
without using procedure overloads.
In the first code snippet, a **ToString** procedure is implemented. This takes a Variant value
and inspects the type of the value to delegate to different implementations. If the caller
passes a value of a different type than Integer, Date, and Text, an empty string will be
returned. This can lead to bugs that will only show up at runtime.

```
AL
```
## Reasons for using procedure overload

## Remarks

## Example

```
codeunit 10 Stringifier
{
local procedure TextToString(value : Text) : Text
begin
Exit(value);
end;
```

In the second code snippet, we overload the ToString procedure for Text, Date and
Integer. At this point, it is not possible for a caller to call a ToString method with a
different type other than Integer, Date, or Text. This will catch the bug above at compile
time.

```
AL
```
```
local procedure DateToString(value : Date) : Text
begin
Exit(Format(value));
end;
local procedure IntegerToString(value : Integer) : Text
begin
Exit(Format(value));
end;
```
```
procedure ToString(value: Variant) : Text
begin
if value.IsInteger then
Exit(IntegerToString(value))
else if value.IsDate then
Exit(DateToString(value))
else if value.IsText then
Exit(TextToString(value))
else
Exit('');
end;
}
```
```
codeunit 10 StringifierWithOverloads
{
procedure ToString(value : Text) : Text
begin
Exit(value);
end;
procedure ToString(value : Date) : Text
begin
Exit(Format(value));
end;
procedure ToString(value : Integer) : Text
begin
Exit(Format(value));
end;
}
```
### Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

AL method reference
AL development environment

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Joker data type

Article•11/25/2024

The Joker data type is an _internal_ data type that isn't exposed to AL developers. Joker
can replace any other type and represents a wildcard. In certain cases, Joker plays the

role of a generic T which is inferred from the type of the left-hand side of the invocation
expression, in other cases, it is inferred from another parameter.

The following illustrates examples of how Joker is used in AL.

```
AL
```
```
AL
```
```
AL
```
AL method reference
AL development environment

```
procedure SetRange(Field: Joker, [FromValue: Joker], [ToValue: Joker])
```
```
procedure SetFilter(Field: Joker, String: Text, [Value: Joker, ...])
```
```
procedure SetAscending(Field: Joker, Ascending: Boolean)
```
## Related information

```
 Yes  No
```

# Action Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the action that the user took on the page.

```
Member Description
None Represents the result of running a page.
```
```
OK Represents the result of the user closing a page window by performing one of
the following actions:
```
- Chooses the **OK** button.
- Chooses the **X** button when there was no **Cancel** button on the window.
- Presses the Esc key when there is no **Cancel** button on the window.
Cancel Represents the result of the user closing a page window by performing one of
the following actions:
- Chooses the **Cancel** button.
- Chooses the **X** button when there is a **Cancel** button on the window.
- Presses the Esc key when there is a **Cancel** button on the window

```
LookupOK Represents the result of the user closing a lookup window by performing one of
the following actions:
```
- Chooses the **OK** button.
- Chooses an item in the Lookup window.
LookupCancel Represents the result of the user closing a lookup window by choosing the
**Cancel** button.

```
Yes Represents the result of the user closing a confirmation window by choosing the
Yes button.
```
```
No Represents the result of the user closing a confirmation window by performing
one of the following actions:
```
- Chooses the No button.
- Chooses the X button.
- Presses the Esc key.
RunObject Represents the result of the user selecting an option that ran another object.

## Members

```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Member Description
RunSystem Represents the result of the user selecting an option that ran an external
program.
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# AuditCategory Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 7.0.
```
Represents an audit category for IfX audit telemetry.

```
Member Description
Other Identifies other audit category.
```
```
UserManagement Identifies user management audit category.
GroupManagement Identifies group managemenet audit category.
```
```
Authentication Identifies authentication audit category.
Authorization Identifies authorization audit category.
```
```
RoleManagement Identifies role management audit category.
ApplicationManagement Identifies application management audit category.
```
```
KeyManagement Identifies key management audit category.
DirectoryManagement Identifies directory management audit category.
```
```
ResourceManagement Identifies resource management audit category.
PolicyManagement Identifies policy management audit category.
```
```
DeviceManagement Identifies device management audit category.
EntitlementManagement Identifies entitlement management audit category.
```
```
PasswordManagement Identifies password management audit category.
IdentityProtection Identifies identity protection audit category.
```
```
ObjectManagement Identifies object management audit category.
ProvisioningManagement Identifies provisioning management audit category.
```
```
CustomerFacing Identifies customer facing audit category.
```
## Members

```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Member Description
Euii Identifies Euii (end user identifiable information) audit category.
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# ClientType Option Type

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the type of the client executing the operation.

```
Member Description
Background A background session.
```
```
ChildSession A child session.
Desktop A desktop client.
```
```
Management A management client.
NAS A NAS client.
```
```
OData A NAS client.
Phone Microsoft Dynamics Business Central Phone client.
```
```
SOAP A SOAP client.
Tablet Microsoft Dynamics Business Central Tablet client.
```
```
Web Microsoft Dynamics Business Central Web client.
Windows Microsoft Dynamics Business Central Windows client.
```
```
Current Microsoft Dynamics Business Central Windows client.
Default The default client.
```
```
ODataV4 A ODataV4 client.
Api An API client.
```
```
Teams Microsoft Teams client.
```
## Members

```
ﾉ Expand table
```
## Remarks


#### Feedback

**Was this page helpful?**

Provide product feedback

Some of these client types don't allow AL code that interacts with the user, such as using
the methods Dialog.Open, Dialog.Update, Window.Open, Window.Update, or System.Error.

If the same codeunit needs to run both in the UI and also in the background (in a
scheduled task or with a job queue entry), or in a web service call (SOAP/OData/API),
then use if GuiAllowed() then calls to encapsulate AL code that interacts with the user.

For more information, see System.GuiAllowed() Method.

System.GuiAllowed() Method
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# CommitBehavior Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 6.0.
```
Specifies whether commit is allowed within the scope of the method.

```
Member Description
Ignore Ignore commits within the scope of this method.
```
```
Error Throw an error when a commit is attempted within the scope of this method.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# DataScope Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 2.0.
```
Identifies the scope of stored data in the isolated storage.

```
Member Description
Module Indicates that the record is available in the scope of the app(extension)
context.
Company Indicates that the record is available in the scope of the company within the
app context.
```
```
User Indicates that the record is available for a user within the app context.
CompanyAndUser Indicates that the record is available for a user and specific company within
the app context.
```
Get Started with AL
Developing Extensions
Isolated Storage

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# DefaultLayout Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
The default layout to be used by a report.

```
Member Description
None The default layout is not set.
```
```
RDLC The default layout is RDLC.
Word The default layout is Word.
```
```
Excel The default layout is Excel.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ErrorBehavior Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 8.0.
```
Specifies whether errors will be collected within the scope of the method.

```
Member Description
Collect Collectable errors will be gathered and code execution will be continued until the end
of the ErrorBehavior scope. If errors are left unhandled at the end of the ErrorBehavior
scope, execution will stop with an aggregated error.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ErrorType Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 3.0.
```
Represents the type of error.

```
Member Description
Client Identifies a client error. The specified message will be shown in the client to the user
and sent to telemetry.
Internal Identifies an internal, the message specified will be sent to telemetry and a generic
error will be displayed to the user.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ExecutionContext Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the context in which a session is running. In certain scenarios, for example
during upgrade, the system will run a session in a special context for a limited time.

```
Member Description
```
```
Normal The normal execution context.
Install An application is being installed.
```
```
Uninstall An application is being uninstalled.
Upgrade An application is being upgraded.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ExecutionMode Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
The execution mode of the current session.

```
Member Description
Standard The session is executing in standard mode.
```
```
Debug The session is executing in debug mode.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# FieldClass Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the type of a field class.

```
Member Description
Normal A normal field.
```
```
FlowField A flow field.
FlowFilter A flow filter.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

# FieldType Option Type

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the type of a table field.

```
Member Description
Boolean Assumes the values true or false. When formatted, a Boolean field is shown as
"Yes" or "No". The size of the corresponding SQL data type, TINYINT, is 1 byte.
Integer Denotes an integer between -2,147,483,647 and 2,147,483,647. The size of the
corresponding SQL data type, INTEGER, is 4 bytes.
```
```
BigInteger A 64-bit integer.
Decimal A decimal number between -10^63 and 10^63. The exponent ranges from -63 to
```
63. Decimal numbers are held in memory with 18 significant digits. The
representation of a decimal number is a Binary Coded Decimal (BCD). The size of
the corresponding SQL data type, DECIMAL(38,20), is 17 bytes. We recommend
that you construct decimals that operate on numbers in the range of +/-
999,999,999,999,999.99. You can construct larger numbers in some cases, but
overflow, truncation or loss of precision can occur.
Option An option field is defined by using an option string, which is a comma-separated
list of strings that represent each valid value of the field. This string is used when a
field of type Option is formatted and its value is converted into a string.
Text Any alphanumeric string. The field must be defined to be between 1 and 2048
characters. The number of bytes used by a text field equals (number of characters
+ 1) * 2. The additional character is used for the string terminating character,
which is '0' in Unicode. The size of a Unicode character is 2 bytes. Therefore, you
multiply the number of characters by two to get the size.

```
Code An alphanumeric string, which is right-justified if the contents are numbers only. If
letters or blanks occur among the numbers, the contents are left-aligned. All
letters are converted to uppercase upon entry. The field must be defined to be
between 1 and 2048 characters.
DateTime Represents a point in time as a combined date and time. The datetime is stored in
the database as Coordinated Universal Time (UTC) and is always displayed as local
```
## Members

```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Member Description
time in Dynamics 365 Business Central.
```
```
Time Any time in the range 00:00:00 to 23:59:59.999. A time field contains 1 plus the
number of milliseconds since 00:00:00 o'clock, or 0 (zero), an undefined time.
Date A date value in the range from January 1, 1753 to December 31, 9999. An
undefined date is expressed as 0. All dates have a corresponding closing date. The
system considers the closing date for a given date as a period that follows the
given date but comes before the next normal date; that is, a closing date is sorted
immediately after the corresponding normal date but before the next normal date.
```
```
DateFormula Used to verify the date entered by the user.
Duration Represents the difference between two points in time, in milliseconds. This value
can be negative.
Guid Globally unique identifier (GUID).
```
```
RecordId Unique record identifier.
TableFilter This data type is used to apply a filter to another table. Currently, this can only be
used to apply security filters from the Permission table.
```
```
Blob Binary Large Object. Used to store bitmaps and memos. Notice that the BLOB is
not stored in the record, but in the BLOB area of the table.
```
```
Media A complex type that encapsulates media files, such as image .jpg and .png files, in
application database tables. The Media data type can be used as a table field data
type, but cannot be used as a variable or parameter.
```
```
MediaSet A complex type that encapsulates media, such as images, in application database
tables. The MediaSet data type can be used as a table field data type, but cannot
be used as variable or parameter.
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# InherentPermissionsScope Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 10.0.
```
The different types of scope that the InherentPermissions attribute can apply to.

```
Member Description
Permissions The Permissions scope
```
```
Entitlements The Entitlements scope
Both The Both scope
```
_InherentPermissionScope_ is used as a parameter with InherentPermissions attribute,
which can override the entitlements. It's an optional method and the default value for
InherentPermissionScope is _Both_ that includes permissions and entitlements. To learn
more about syntax and usage of InherentPermissions attribute, see InherentPermissions
Attribute.

```
AL
```
## Members

```
ﾉ Expand table
```
## Remarks

```
７ Note
```
```
You can use inherent permissions only for objects within the same extension.
```
## Example

```
[InherentPermissions(PermissionObjectType:Table, Database:MyTable, 'x',
InherentPermissionScope:Entitlements)]
```
```
[InherentPermissions(PermissionObjectType:Table, Database:MyTable, 'x',
InherentPermissionScope:Permissions)]
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Getting Started with AL
Developing Extensions
Inherent Permissions

```
[InherentPermissions(PermissionObjectType:Table, Database:MyTable, 'x',
InherentPermissionScope:Both)]
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# IsolationLevel Option Type

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
The isolation level applied for this record.

```
Member Description
Default Follows the table's isolation level for reads, same behavior as not choosing
an IsolationLevel.
ReadUncommitted Allows the record to read uncommitted changes from other transactions.
```
```
ReadCommitted Only allows for reads committed data, but does not guarantee that rows
read will stay consistent throughout the entirety of the transaction.
RepeatableRead Guarantees that rows read will stay consistent during the entirety of the
current transaction. Does not allow reading of uncommitted data.
UpdLock Ensures that the rows read will stay consistent in the entirety of the current
transaction, while also blocking readers with the same isolation level. Does
not allow reading of uncommitted data.
```
Getting Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# NotificationScope Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Specifies the context in which the notification appears in the client.

```
Member Description
GlobalScope The notifications are not directly related to the user's current task. Note:
GlobalScope is currently not supported, so do not use this value.
LocalScope The notification appears in context of the user's current task, on the page the user
is currently working on. This is the default value.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ObjectType Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
The different types of objects.

```
Member Description
Codeunit The Codeunit object type
```
```
MenuSuite The Menusuite object type
Page The Page object type
```
```
Query The Query object type
Report The Report object type
```
```
Table The Table object type
XmlPort The XMLPort object type
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PageBackgroundTaskErrorLevel Option

# Type

Article•08/26/2024

```
Version : Available or changed with runtime version 4.0.
```
Specifies how an error in the page background task appears in the client.

```
Member Description
Error Error occuring in a page background task is displayed as an normal error in the client.
This is the default value.
Warning Error occuring in a page background task is displayed as an warning in the client.
Note: Any error thrown in completion trigger will ignore this value and will be
displayed in the client as a normal error.
Ignore Error occuring in a page background task is not displayed in the client. Note: Any error
thrown in completion trigger will ignore this value and will be displayed in the client as
a normal error.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

# PageStyle Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 14.0.
```
Represents the different kinds of styles that can be applied to page controls.

```
Member Description
None None
```
```
Standard Standard
StandardAccent Blue
```
```
Strong Bold
StrongAccent Blue + Bold
```
```
Attention Red + Italic
AttentionAccent Blue + Italic
```
```
Favorable Bold + Green
Unfavorable Bold + Italic + Red
```
```
Ambiguous Yellow
Subordinate Grey
```
The PageStyle option type can be used to get the valid values for StyleExpr, which is set

on page controls.

```
AL
```
## Members

```
ﾉ Expand table
```
## Example

```
layout
{
area(Content)
```

#### Feedback

**Was this page helpful?**

Provide product feedback

Getting Started with AL
Developing Extensions

```
{
field(Name; rec.Name)
{
StyleExpr = nameStyle;
}
}
}
```
```
var nameStyle : Text;
local procedure ChangeNameStyle(newPageStyle : PageStyle)
begin
nameStyle := format(newPageStyle);
end;
```
### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PermissionObjectType Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 9.0.
```
The different types of objects that can have different permissions assigned.

```
Member Description
TableData The Table Data object type
```
```
Table The Table object type
Report The Report object type
```
```
Codeunit The Codeunit object type
XmlPort The Xml Port object type
```
```
Page The Page object type
Query The Query object type
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# PromptMode Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 12.1.
```
Specifies the current mode of a PromptDialog page.

```
Member Description
Prompt Prompting the user for input for the copilot interaction.
```
```
Generate Generating the output of the copilot interaction.
Content Showing the output of the copilot interaction.
```
Getting Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ReportFormat Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Specifies the format of the report.

```
Member Description
Excel Saves the report as an Excel file.
```
```
Html Saves the report in HTML format.
Pdf Saves the report in PDF format.
```
```
Word Saves the report in Word format.
Xml Saves the report in XML format.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# ReportLayoutType Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 9.0.
```
Represents the type of a report layout.

```
Member Description
RDLC Denotes a report layout of type RDLC.
```
```
Word Denotes a report layout of type Microsoft Word.
Excel Denotes a report layout of type Microsoft Excel.
```
```
Custom Denotes a report layout of a user-defined type.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# SecurityFilter Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Specifies how security filters are applied to the record.

```
Member Description
Validated All security filters are applied to this instance of the record and if any code tries to
access a record that is outside the range of the security filters, then an error occurs.
Filtered All security filters are applied to this instance of the record.
```
```
Ignored All security filters are ignored for this instance of the record.
Disallowed Security filters are not allowed on the record. If any security filters are set, then you
receive an error when you run the object that uses this instance of the record.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# SecurityOperationResult Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 7.0.
```
Represents security audit operation result.

```
Member Description
Success Identifies operation success.
```
```
ClientError Identifies client error in the operation.
Failure Identifies operation failure.
```
```
Timeout Identifies operation timeout.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# TableConnectionType Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Use variables of this data type to specify the type of connection to an external database.

```
Member Description
CRM Specifies the table as an integration table for integrating Dynamics 365
Business Central with Dynamics 365 for Sales. The table is typically based on an
entity in Dynamics 365 for Sales, such as the Accounts entity.
ExternalSQL Specifies the table as a table or view in SQL Server that is not in the Dynamics
365 Business Central database.
Exchange This is for internal use only.
```
```
MicrosoftGraph This is for internal use only.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

# TelemetryScope Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 5.4.
```
Represents the emission scope of the telemetry signal.

```
Member Description
ExtensionPublisher Emit telemetry to extensions publisher's account.
```
```
All Emit telemetry to extension publisher's and partner's telemetry account.
```
```
AL
```
```
AL
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Examples

```
if not FileManagement.ServerFileExists(ServerFile) then begin
LogInternalError(SomethingWentWrongErr,
DataClassification::SystemMetadata, Verbosity::Error);
```
```
if not XmlDocument.ReadFrom('<?xml version="1.0" encoding="UTF-8"?>' +
'<Elster xmlns="' + XmlNameSpace + '"></Elster>', XmlSubDoc) then
LogInternalError(XMLDocHasNotBeenCreatedErr,
DataClassification::SystemMetadata, Verbosity::Error);
```
## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

# TestPermissions Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Specifies a value that can be used to determine which permission sets are used on tests
that are run by test codunits or test functions.

```
Member Description
```
```
InheritFromTestCodeunit Is only relevant for test methods; not test codeunits. It specifies that a
test method uses the TestPermissions property setting of the test
codeunit to which it belongs. If you use this value on a test codunit,
the property will resolve to Restrictive at runtime.
Restrictive This is the default value. Setting the Restrictive value will cause the
permission execution context of every test in the codeunit to be set by
default to 'D365 Full Access’. It is required to lower the level of
permissions within every test to any permission sets other than 'D365
Full Access’. Otherwise, it will result in a runtime error. The change of
the permission execution context is supported by Codeunit "Library -
Lower Permissions".
NonRestrictive Setting the NonRestrictive value will cause that the permission
execution context of every test in the codeunit is set to 'D365 Full
Access’. Opposite to Restrictive, setting the TestPermissions property
to NonRestrictive does not require a change of permissions.
Disabled Setting this value will exclude any change of the permission execution
context and all tests will be executed using SUPER.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information


**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# TextEncoding Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents a file encoding.

```
Member Description
MSDos MSDos encoding.
```
```
UTF8 UTF8 encoding.
UTF16 UTF16 encoding.
```
```
Windows Windows encoding.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# TransactionModel Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents a test transaction model.

```
Member Description
AutoCommit The transaction automatically commits after the Test method has run.
```
```
AutoRollback The transaction is automatically rolled back after the Test method has run.
None No write-transaction is open in the test-method code, and writes will fail. The
transaction model mirrors the model used by the "real" client. Every call from the
TestPage to the "server" has its own transaction.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

# TransactionType Option Type

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents a transaction type.

```
Member Description
UpdateNoLocks This is an update transaction. Modifications can occur within the transaction. All
read operations are performed with READ UNCOMMITTED locking until the
table is either modified by a write operation or locked with the LOCKTABLE
Method (Record). From this point until the end of the transaction, all read
operations are performed with UpdLock locking. This transaction type improves
concurrency for all tables that users access within the transaction by delaying
locking as much as it can. However, the disadvantage is that you must know
when to lock the tables for the required transaction behavior.
```
```
Update This is an update transaction. Modifications can occur within the transaction. All
read operations are performed with REPEATABLE READ locking until the table is
either modified by any write operation or locked with the LOCKTABLE method.
From this point forward, all read operations are performed with UpdLock
locking. This transaction type provides full transaction isolation from the start
of the transaction, regardless of the lock status of tables that users access
within the transaction.
```
```
Snapshot This is a read-only transaction. Modifications cannot occur within the
transaction. All read operations are performed with REPEATABLE READ locking.
Therefore, shared locks are added on all data and are maintained until the end
of the transaction. This prevents other transactions from modifying any rows
that have been read by the current transaction.
Browse This is a read-only transaction. Modifications cannot occur within the
transaction. All read operations are performed with READ UNCOMMITTED
locking. Therefore, no locks are added and locks that are added by other
sessions are not honored. This means that the transaction may read
uncommitted data.
```
```
Report Report option maps to one of the basic options. This enables a report to use
the most concurrent read-only form of data access for the connected server.
```
## Members

```
ﾉ Expand table
```

#### Feedback

**Was this page helpful?**

Provide product feedback

```
Member Description
When you use Dynamics 365 Business Central database server, it maps to
Snapshot and when you use SQL Server, it maps to Browse.
```
Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Verbosity Option Type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Represents the security level of events.

```
Member Description
Critical Identifies an abnormal exit or termination event.
```
```
Error Identifies a severe error event.
Warning Identifies a warning event such as an allocation failure.
```
```
Normal Identifies a non-error event such as an entry or exit event.
Verbose Identifies a detailed trace event.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# WebServiceActionResultCode Option

# Type

Article•10/01/2024

```
Version : Available or changed with runtime version 2.0.
```
Represents a web service action status code.

```
Member Description
None No status code.
```
```
Get Item read.
Created Item created.
```
```
Updated Item updated.
Deleted Item deleted.
```
Get Started with AL
Developing Extensions

## Members

```
ﾉ Expand table
```
## Related information

```
 Yes  No
```

## Feedback

**Was this page helpful?**

Provide product feedback

# Any Data type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
This data type can be substituted by any other data type.

Get Started with AL
Developing Extensions

```
７ Note
```
```
The Any Data type cannot be used for declaring constructs in AL. Any is a type that
is used for the parameters or return type of methods in the platform.
```
## Related information

```
 Yes  No
```

# BigInteger Data type

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Stores very large whole numbers that range from -9,223,372,036,854,775,807 to
9,223,372,036,854,775,807.

This data type is a 64-bit integer.

You must add an L to the constant definition to inform AL that the integer must be
interpreted and treated as a BigInteger.

If you assign -9,223,372,036,854,775,808 directly to a BigInteger variable, then you get
an error when you try to compile the code. However, you can indirectly assign
-9,223,372,036,854,775,808 to a BigInteger variable by using the following code.

```
AL
```
If you try to indirectly assign a value that is smaller than -9,223,372,036,854,775,808, or
larger than 9,223,372,036,854,775,807, then you get a run-time error.

```
AL
```
Get Started with AL
Developing Extensions

## Remarks

```
BigIntegerVar := -9223372036854775807L;
BigIntegerVar := BigIntegerVar - 1 ;
```
## Example

```
BI := 1 L;
BI := 455500000000 L;
```
## Related information


#### Feedback

**Was this page helpful?**

Provide product feedback

```
 Yes  No
```

# BigText Data type

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Handles large text documents.

The following methods are available on instances of the BigText data type.

```
Method name Description
```
```
AddText(Text [, Integer]) Adds a text string to a BigText variable.
AddText(BigText [, Integer]) Adds a text string to a BigText variable.
```
```
GetSubText(var Text, Integer [,
Integer])
```
```
Gets part of a BigText variable.
```
```
GetSubText(var BigText, Integer [,
Integer])
```
```
Gets part of a BigText variable.
```
```
Length() Retrieves the length of the text stored in this BigText
instance.
Read(InStream) Streams a BigText object that is stored as a BLOB in a table
to a BigText variable.
```
```
TextPos(Text) Gets the position at which a specific string first occurs in this
BigText instance.
```
```
Write(OutStream) Streams a BigText object to a BLOB field in a table.
```
This data type cannot be shown in a message window or be seen in the Debugger. The
maximum length of a BigText variable is 2,147,483,647 characters and this corresponds
to 2 GB. You can use the BigText methods to manipulate a BigText variable, for example
to extract part of a BigText variable or to add a text string to a BigText variable. The
normal string methods cannot be used with a BigText variable.

## Instance methods

```
ﾉ Expand table
```
## Remarks


#### Feedback

**Was this page helpful?**

Provide product feedback

Get Started with AL
Developing Extensions

### Related information

```
 Yes  No
```

# BigText.AddText(Text [, Integer])

# Method

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Adds a text string to a BigText variable.

```
AL
```
_BigText_
Type: BigText
An instance of the BigText data type.

_String_
Type: Text
The string that will be added to the BigText variable. If this parameter is empty, then the
BigText variable is not modified.

_[Optional] Position_
Type: Integer
This is an optional parameter that defines the position in the BigText variable where the
string is inserted. If this parameter is omitted, then the string is added at the end of the
BigText variable. If this parameter is less than one, then a run-time error occurs. If this
parameter is greater than the length of the BigText variable, then the string is added at
the end of the BigText variable.

_Variable_ can be inserted anywhere in _BigText_ or added at the end of the _BigText_.

The first character in a _BigText_ variable is position 1.

## Syntax

```
BigText.AddText(String: Text [, Position: Integer])
```
## Parameters

## Remarks


To delete the content in a _BigText_ variable, use the Clear Method. The following code
shows the syntax for the method: Clear(BigText)

The following examples show how to use the AddText method. The specified text is
inserted into the BigText string at the specified position. In these examples, the initial
content of the _BigText_ variable is ABCDEFG. These examples require that you create the

following variable.

```
AL
```
The following example inserts the string 'ZZZ' after the character B in the MyBigText
variable because 3 is specified for _Position_.

```
AL
```
The following example appends the string 'ZZZ' at the end of the MyBigText variable
because the number specified for _Position_ is greater than the length of the MyBigText
variable.

```
７ Note
```
```
If you use AddText to add multiple BigText strings to what is presented as a single
string, you can experience performance problems. The same applies to other
repetitive uses of AddText. This is due to the implementation of the BigText data
type, which relies on a String object that is immutable. You can avoid this issue by
refactoring the code to reduce the number of additions or deletions. Alternatively,
you can change your implementation to use the System.Text.StringBuilder class
instead. For more information, see Immutability and the StringBuilder Class in the
MSDN Library.
```
### Example 1

```
var
MyBigText: BigText;
```
```
// Example 1
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('ZZZ', 3 ); // Returns the subtext ABZZZCDEFG.
```
### Example 2


#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
In the following example, the content of the MyBigText variable is unchanged because
the specified variable is an empty string.

```
AL
```
In the following example, the method returns an error because 0 is specified for _Position_.

```
AL
```
BigText Data Type
Get Started with AL
Developing Extensions

```
// Example 2
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('ZZZ', 15 ); // Returns the subtext ABCDEFGZZZ.
```
### Example 3

```
// Example 3
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('', 1 ); // Returns the subtext ABCDEFG.
```
### Example 4

```
// Example 4
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('ZZZ', 0 ); // Returns an error.
```
### Related information

```
 Yes  No
```

# BigText.AddText(BigText [, Integer])

# Method

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Adds a text string to a BigText variable.

```
AL
```
_BigText_
Type: BigText
An instance of the BigText data type.

_String_
Type: BigText
The string that will be added to the BigText variable. If this parameter is empty, then the
BigText variable is not modified.

_[Optional] Position_
Type: Integer
This is an optional parameter that defines the position in the BigText variable where the
string is inserted. If this parameter is omitted, then the string is added at the end of the
BigText variable. If this parameter is less than one, then a run-time error occurs. If this
parameter is greater than the length of the BigText variable, then the string is added at
the end of the BigText variable.

_Variable_ can be inserted anywhere in _BigText_ or added at the end of the _BigText_.

The first character in a _BigText_ variable is position 1.

## Syntax

```
BigText.AddText(String: BigText [, Position: Integer])
```
## Parameters

## Remarks


To delete the content in a _BigText_ variable, use the Clear Method. The following code
shows the syntax for the method: Clear(BigText)

The following examples show how to use the AddText method. The specified text is
inserted into the BigText string at the specified position. In these examples, the initial
content of the _BigText_ variable is ABCDEFG. These examples require that you create the

following variable.

```
AL
```
The following example inserts the string 'ZZZ' after the character B in the MyBigText
variable because 3 is specified for _Position_.

```
AL
```
The following example appends the string 'ZZZ' at the end of the MyBigText variable
because the number specified for _Position_ is greater than the length of the MyBigText
variable.

```
７ Note
```
```
If you use AddText to add multiple BigText strings to what is presented as a single
string, you can experience performance problems. The same applies to other
repetitive uses of AddText. This is due to the implementation of the BigText data
type, which relies on a String object that is immutable. You can avoid this issue by
refactoring the code to reduce the number of additions or deletions. Alternatively,
you can change your implementation to use the System.Text.StringBuilder class
instead. For more information, see Immutability and the StringBuilder Class in the
MSDN Library.
```
### Example 1

```
var
MyBigText: BigText;
```
```
// Example 1
MyBigText.AddTEXT('ABCDEFG');
MyBigText.AddTEXT('ZZZ', 3 ); // Returns the subtext ABZZZCDEFG.
```
### Example 2


#### Feedback

**Was this page helpful?**

Provide product feedback

```
AL
```
In the following example, the content of the MyBigText variable is unchanged because
the specified variable is an empty string.

```
AL
```
In the following example, the method returns an error because 0 is specified for _Position_.

```
AL
```
BigText Data Type
Get Started with AL
Developing Extensions

```
// Example 2
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('ZZZ', 15 ); // Returns the subtext ABCDEFGZZZ.
```
### Example 3

```
// Example 3
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('', 1 ); // Returns the subtext ABCDEFG.
```
### Example 4

```
// Example 4
MyBigText.AddText('ABCDEFG');
MyBigText.AddText('ZZZ', 0 ); // Returns an error.
```
### Related information

```
 Yes  No
```

# BigText.GetSubText(var Text, Integer [,

# Integer]) Method

Article•08/26/2024

```
Version : Available or changed with runtime version 1.0.
```
Gets part of a BigText variable.

```
AL
```
_BigText_
Type: BigText
An instance of the BigText data type.

_Variable_
Type: Text
The sub text of the BigText that is retrieved. This is the actual text that is returned.

_Position_
Type: Integer
The position in the BigText variable that the sub text is to be retrieved from. If this
parameter is less than one, then a run-time error occurs. If this parameter is greater than
the length of the BigText variable, then an empty string is returned. If the value of this
parameter plus the value of the Length parameter is greater than the length of the
BigText variable, then the remainder of the BigText variable from the position specified
by this parameter is returned.

_[Optional] Length_
Type: Integer
The length of the sub text that should be retrieved. This parameter is optional. If this
parameter is omitted the function retrieves a sub text that starts at Position and runs to
the end of the BigText variable. If this parameter is less than 0, then a run-time error

## Syntax

```
[Length := ] BigText.GetSubText(var Variable: Text, Position: Integer [,
Length: Integer])
```
## Parameters


occurs. If the value of the Position parameter plus the value of this parameter is greater
than the length of the BigText variable, then the remainder of the BigText variable from
the position specified by this parameter is returned.

_[Optional] Length_
Type: Integer
The length of the result text.

The first character in a BigText variable is position 1.

To delete the content in a BigText variable use the Clear Method. The following code
snippet shows the syntax for the clear method. Clear(BigText).

The following examples demonstrate how to use the GetSubText method. This example
requires that you create the following global variables and text constant.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method starts from the third position (the character C) in the MyBigText
variable and retrieves two characters. The result is the subtext CD. This is because the
number 2 is specified for _Length_.

```
AL
```
### Return Value

### Remarks

### Example 1

```
var
MyBigText: BigText;
VarSubText: Text;
Text000: Label 'VarSubText = %1';
```
```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 3 , 2 ); // Returns CD.
Message(Text000, VarSubText);
```
### Example 2


The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an error because zero is specified for _Position_.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an error because a negative number is specified for
_Length_.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an empty string because the number specified for _position_
is greater than the length of the MyBigText variable.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method starts from the forth position (the character D) and retrieves all
the characters in the MyBigText string. The result is the subtext DEFG. This is because the
number specified for _Length_ is greater than the length of the MyBigText variable.

```
AL
```
```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 0 , 4 ); // Returns an error.
Message(Text000, VarSubText);
```
### Example 3

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 5 , - 2 ); // Returns an error.
Message(Text000, VarSubText);
```
### Example 4

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 15 , 4 ); // Returns an empty string.
Message(Text000, VarSubText);
```
### Example 5


#### Feedback

**Was this page helpful?**

Provide product feedback

BigText Data Type
Get Started with AL
Developing Extensions

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 4 , 15 ); // Returns DEFG.
Message(Text000, VarSubText);
```
### Related information

```
 Yes  No
```

# BigText.GetSubText(var BigText, Integer

# [, Integer]) Method

Article•10/01/2024

```
Version : Available or changed with runtime version 1.0.
```
Gets part of a BigText variable.

```
AL
```
_BigText_
Type: BigText
An instance of the BigText data type.

_Variable_
Type: BigText
The sub text of the BigText that is retrieved. This is the actual text that is returned.

_Position_
Type: Integer
The position in the BigText variable that the sub text is to be retrieved from. If this
parameter is less than one, then a run-time error occurs. If this parameter is greater than
the length of the BigText variable, then an empty string is returned. If the value of this
parameter plus the value of the Length parameter is greater than the length of the
BigText variable, then the remainder of the BigText variable from the position specified
by this parameter is returned.

_[Optional] Length_
Type: Integer
The length of the sub text that should be retrieved. This parameter is optional. If this
parameter is omitted the method retrieves a sub text that starts at Position and runs to
the end of the BigText variable. If this parameter is less than 0, then a run-time error

## Syntax

```
[Length := ] BigText.GetSubText(var Variable: BigText, Position: Integer [,
Length: Integer])
```
## Parameters


occurs. If the value of the Position parameter plus the value of this parameter is greater
than the length of the BigText variable, then the remainder of the BigText variable from
the position specified by this parameter is returned.

_[Optional] Length_
Type: Integer
The length of the result text.

The first character in a BigText variable is position 1.

To delete the content in a BigText variable use the Clear Method. The following code
snippet shows the syntax for the clear method. Clear(BigText).

The following examples demonstrate how to use the GetSubText method. This example
requires that you create the following global variables and text constant.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method starts from the third position (the character C) in the MyBigText
variable and retrieves two characters. The result is the subtext CD. This is because the
number 2 is specified for _Length_.

```
AL
```
### Return Value

### Remarks

### Example 1

```
var
MyBigText: BigText;
VarSubText: Text;
Text000: Label 'VarSubText = %1';
```
```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 3 , 2 ); // Returns CD.
Message(Text000, VarSubText);
```

The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an error because zero is specified for _Position_.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an error because a negative number is specified for
_Length_.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method returns an empty string because the number specified for _position_

is greater than the length of the MyBigText variable.

```
AL
```
The following example initializes the content of the MyBigText variable with the text
ABCDEFG. The method starts from the forth position (the character D) and retrieves all

### Example 2

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 0 , 4 ); // Returns an error.
Message(Text000, VarSubText);
```
### Example 3

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 5 , - 2 ); // Returns an error.
Message(Text000, VarSubText);
```
### Example 4

```
MyBigText.AddText('ABCDEFG');
MyBigText.GetSubText(VarSubText, 15 , 4 ); // Returns an empty string.
Message(Text000, VarSubText);
```
### Example 5


#### Feedback

**Was this page helpful?**

Provide product feedback


```
AL
```

```
