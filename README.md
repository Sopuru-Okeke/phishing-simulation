# phishing-simulation
phishing simulation using Gophish and Localtonet


This project showcases a beginner-level phishing simulation using [Gophish](https://sourceforge.net/projects/gophish.mirror/), a powerful open-source phishing framework.
The goal was to better understand how phishing campaigns are created, launched, and tracked.
I used **Gophish** along with **Localtonet** to ensure that the phishing mail could be accessed outside my localhost. 
I created the campaign with custom email and landing page templates.

## Tools & Technologies

- [Gophish](https://sourceforge.net/projects/gophish.mirror/)
- Localtonet (for exposing localhost)
- HTML/CSS (for email template and landing page cloning)

## Project Structure

- `email-templates/` — contains the custom Facebook phishing email template
- `landing-pages/` — cloned Facebook login page HTML and assets
- `screenshots/` — screenshots of campaign results and setup

## How It Works

1. The phishing email mimics a Facebook security alert, warning about suspicious login attempts.
2. The email contains a link to the cloned Facebook login page.
3. When a user clicks the link, they are taken to the fake page where login credentials can be captured.
4. The Gophish server records interactions, allowing tracking and analysis.
5. Localtonet tunnels the local server to a public URL for testing with real email recipients (ethical testing only).

## Lessons Learned
- How phishing emails are structured to look authentic
- Techniques for cloning legitimate websites for phishing simulations
- Using Gophish to manage phishing campaigns and track user activity
- Exposing a local server securely using Localtonet

## Disclaimer
This project is for educational purposes only and should be used ethically and legally.
Unauthorized phishing or use against real targets without permission is illegal and unethical.
