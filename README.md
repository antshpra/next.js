- Match Criteria
  - sender
- Match Data
- Action Type:
  - etd - estimated time of deletion
- Action Data:
  - etd: [ hrs, archive / delete on read, delete skipped / historical ]

<br/>

BigQuery
- **raw**
  - com_gmail_antshpra
  - com_gmail_antshpra-actions
  - com_gmail_prashantgupta_bits
  - com_gmail_prashantgupta_bits-actions
  - com_gmail_gupta_disha30
  - com_gmail_gupta_disha30-actions
  - in_zero65_prashant
  - in_zero65_prashant-actions
- **cleaned** - removing duplicates, extracting email
  - com_gmail_antshpra
  - com_gmail_antshpra-actions
  - com_gmail_prashantgupta_bits
  - com_gmail_prashantgupta_bits-actions
  - com_gmail_gupta_disha30
  - com_gmail_gupta_disha30-actions
  - in_zero65_prashant
  - in_zero65_prashant-actions
- **modeled** - aggregating by email
  - com_gmail_antshpra
  - com_gmail_prashantgupta_bits
  - com_gmail_gupta_disha30
  - in_zero65_prashant
- **prepared**
  - emails
  - domains
