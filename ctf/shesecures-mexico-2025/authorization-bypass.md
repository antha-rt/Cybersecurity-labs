# Authorization bypass
## Web application logic manipulation

## Objective

Identify weaknesses in the logic of a legacy web interface controlling access to a restricted system.

---

## Approach

Examined client-side code and discovered a parameterized request referencing an administrative endpoint.

Tested variations of the parameter value to observe application behavior.

Identified an improper authorization check allowing access when manipulating the parameter value.

---

## Result

Parameter manipulation allowed unauthorized access to protected content.

---

## Skills demonstrated

- Parameter tampering

- Authorization bypass analysis

- Web application testing

- Understanding of insecure access controls