# Validator
## Usage

dependent on [Flash](https://github.com/sashagar86/Flash)

```Validator::is_not_looged_in()``` check user on not login. Return true/false

```Validator::is_admin()``` check user having admin role. Return true/false

```Validator::isEmail($email)``` check email using `filter_var` with `FILTER_VALIDATE_EMAIL`. $email - string. Return true/false

```Validator::requiredFields($requiredFields)```. Check required fields on empty value. Return true/false and set message if field is empty. $requiredFields is array of required fields


