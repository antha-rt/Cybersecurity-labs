# Web Hidden Endpoint

## Objective

Access a restricted area of a university cloud storage system without valid user credentials.

---

## Approach

Inspected the HTML source code of the login interface.

Discovered a developer comment referencing a hidden endpoint used for debugging.

Manually navigated to the referenced path.

The endpoint exposed sensitive information that should not have been publicly accessible.

---

## Result

The debug endpoint revealed the challenge key.

---

## Skills demonstrated

- Web application reconnaissance

- Source code inspection

- Discovery of hidden endpoints

- Understanding of common developer misconfigurations