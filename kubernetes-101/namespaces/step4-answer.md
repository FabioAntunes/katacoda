##Exercises

**Exercise 1:-**
Create a namespace titled `exercise` using the `kubectl` CLI.

`kubectl create namespace exercise`{{execute}}
**Exercise 2:-**
Create a namespace titled `yaml` using the YAML manifest using the `exercise.yaml`{{open}} file.

<pre class="file"
data-filename="exercise.yaml"
data-target="replace">
apiVersion: v1
kind: Namespace
metadata:
  name: yaml</pre>