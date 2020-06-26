# A K8s based file-server journal application with Redis backend

The frontend application is a Node.js application implemented in
TypeScript and exposes HTTP on port 8080. It servers requests to the
path /api/* and uses Redis backend to add, delete or return journal
entries.

## 