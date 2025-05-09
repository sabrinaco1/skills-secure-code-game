echo "Test for Dependabot check" >> test-dependabot-check.txt
git add test-dependabot-check.txt
git commit -m "Test PR to trigger Dependabot workflow"
git push origin test-dependabot-check
