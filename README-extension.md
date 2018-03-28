# Extending the Nucleus

Downstream images can add executable scripts in `/opt/image-extension` and they will be executed using the `run-parts` command prior to the Jenkins agent launching. For example, this can be used to automatically decrypt assets needed for particular types of jobs without having to embed that logic in every job definition that will run on an image.
