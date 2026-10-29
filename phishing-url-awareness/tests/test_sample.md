# Test Samples and Results

| Sample URL | Observed Warning Signs / Findings |
| :--- | :--- |
| `http://192.0.2.10/account` | - Uses an IP address instead of a familiar domain.<br>- Uses HTTP. HTTPS alone does not prove trust. |
| `https://example.com@phish-site.com/login` | - Contains an @ symbol; inspect carefully. |
| `http://secure-login-update-account-verification-service-portal.com` | - Unusually long URL (over 100 characters).<br>- Contains many hostname segments/subdomains.<br>- Uses HTTP. |
| `http://xn--80akhbyknj4f.com/login` | - Contains a punycode-style hostname.<br>- Uses HTTP. |
| `https://safe-domain.com` | - No listed warning signs found. This does NOT prove safety. |
