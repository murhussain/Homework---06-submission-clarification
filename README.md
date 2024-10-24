# Network ACL Assignment-6 --- Submission Details

## What You Need to Submit
1. PDF Report
2. Video Recording
3. Packet Tracer (.pkt) file

## Video Documentation Guidelines
👉 **FOCUS ON SHOWING TESTS, NOT CONFIGURATIONS**
- Record yourself testing each ACL requirement using Packet Tracer
- DO NOT waste time recording yourself typing ACL configurations
- Your .pkt file will show your configurations to TAs

### What to Show in Your Video:
✅ Test and verify each requirement:
- HR accessing Finance department services
- Finance department accessing only web services (HTTP/HTTPS) in HR
- Marketing being blocked from Finance but having internet access
- File Server access tests:
  * Finance department FTP upload capability
  * Other departments' read-only access
- Specific HR hosts (192.168.10.10, 192.168.10.15) accessing internet
- Log entries showing denied traffic to/from Finance

## Report Content Requirements
Your PDF report should include:

1. **Test Results for Each ACL Requirement**
   - Screenshots of successful/failed pings
   - Web access tests
   - FTP access tests
   - Log entries for denied traffic

2. **Brief Explanations**
   - Which ACL achieves each requirement
   - Where each ACL is applied
   - Why you chose that implementation

## What NOT to Include
❌ DO NOT document:
- Basic router configurations
- Interface setups
- IP addressing
- Routing protocols
- VLAN configurations
- Basic connectivity commands

## Common Questions Answered
1. **Q: Do I need to show basic device configurations?**
   A: No, focus only on ACL-related tests and results.

2. **Q: Should I show routing protocol configurations?**
   A: No, TAs will see these in your .pkt file.

3. **Q: What should my video mainly show?**
   A: Show tests proving your ACLs work - successful and failed access attempts based on requirements.

4. **Q: Do I need to explain every command used?**
   A: No, explain only ACL implementation decisions and show test results.

## Important Notes
- Use simulation mode in Packet Tracer for clear traffic flow demonstration
- Show both successful and failed access attempts
- Include relevant error messages or success indicators
- Focus on proving your ACLs work as required
- Your .pkt file will contain all configurations - no need to document basic setups

## Grading Focus
TAs will evaluate:
- ACL functionality through your test results
- Correct implementation of security requirements
- Proper documentation of test results
- Clear demonstration of working/blocked access
- Logging functionality for Finance department

Remember: The goal is to prove your ACLs work correctly, not to document every network configuration detail.
