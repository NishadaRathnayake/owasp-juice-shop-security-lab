# HTTP Headers Reconnaissance

## Command

```bash
curl -I http://localhost:3000

```markdown
## Result

The application returned an HTTP 200 OK response.

Important headers observed:

- Access-Control-Allow-Origin: *
- X-Content-Type-Options: nosniff
- X-Frame-Options: SAMEORIGIN
- Feature-Policy: payment 'self'
- X-Recruiting: #/jobs
- Cache-Control: public, max-age=0
- Content-Type: text/html; charset=UTF-8

## Observation

The HTTP response headers provide information about the web application's
security configuration and server behavior.

The presence of security-related headers such as X-Content-Type-Options
and X-Frame-Options was identified during reconnaissance.

The Access-Control-Allow-Origin header was also observed and will be
considered during later security testing.

## Evidence

The command output was captured from the locally hosted OWASP Juice Shop
application running on localhost:3000.
