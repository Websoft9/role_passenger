Ansible Role: Passenger
=========

This Role used for install application Server [Passenger](https://www.phusionpassenger.com/) which is a fast and robust web server and application server for Ruby, Python and Node.js

## Requirements

Make sure these requirements need before the installation

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu18.04 AmazonLinux|
| Python version | Python2  |
| Python Components |    |
| Runtime | one of python,ruby,node |


## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before

```
  roles:
    - {role: role_common, tags: "role_common"}
    - {role: role_template, tags: "role_apache"}
    - {role: role_template, tags: "role_nginx"}
    - {role: role_template, tags: "role_python"}
    - {role: role_template, tags: "role_ruby"}
```

## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| template_applications | True, False | Boolean | No |

notes: 

1. ×××××××
2. ×××××××

## Example

```

```

## FAQ

1. Every role name must start with **role_**
2. Minimal dependence other roles
3. Variable must reasonable, and program syntax complete
