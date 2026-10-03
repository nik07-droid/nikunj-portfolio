# Render deployment

This portfolio is a static HTML, CSS, and JavaScript site. It needs no database, server, secrets, or environment variables.

Push this directory to a GitHub, GitLab, or Bitbucket repository. Keep the `dist` directory in source control.

Render settings:
- Service: Static Site
- Build command: `echo "Static portfolio ready"`
- Publish directory: `dist`
- Automatic deploys: enabled

The included render.yaml also supports Blueprint deployment.
