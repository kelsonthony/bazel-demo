# Bazel Demo 


## Example https://www.baeldung.com/bazel-build-tool 
## Commands 

bazel build //...

bazel run bazel-demo 

bazel query --tool_tag=ijwb:IDEA:community --output=label_kind --keep_going "attr('tags', '^((?!manual).)*$', //...:all)" --