<!--

classDiagram
class events{
 *TEXT id NOT NULL
   TEXT author NOT NULL
   TEXT content NOT NULL
   INTEGER created_at NOT NULL
   TEXT d_tag_value
   INTEGER kind NOT NULL
   TEXT pubkey NOT NULL
   TEXT sig NOT NULL
   TEXT tags NOT NULL
}
class generic_tags{
 *TEXT event_id NOT NULL
   *TEXT tag NOT NULL
   TEXT author NOT NULL
   INTEGER created_at NOT NULL
   INTEGER kind NOT NULL
}
class nostr_relay_migrations{
 *INTEGER id
   INTEGER created_at NOT NULL
   TEXT name NOT NULL
}
events "1" -- "0..n" generic_tags

-->
![](https://mermaid.ink/img/Y2xhc3NEaWFncmFtCmNsYXNzIGV2ZW50c3sKICpURVhUIGlkIE5PVCBOVUxMCiAgIFRFWFQgYXV0aG9yIE5PVCBOVUxMCiAgIFRFWFQgY29udGVudCBOT1QgTlVMTAogICBJTlRFR0VSIGNyZWF0ZWRfYXQgTk9UIE5VTEwKICAgVEVYVCBkX3RhZ192YWx1ZQogICBJTlRFR0VSIGtpbmQgTk9UIE5VTEwKICAgVEVYVCBwdWJrZXkgTk9UIE5VTEwKICAgVEVYVCBzaWcgTk9UIE5VTEwKICAgVEVYVCB0YWdzIE5PVCBOVUxMCn0KY2xhc3MgZ2VuZXJpY190YWdzewogKlRFWFQgZXZlbnRfaWQgTk9UIE5VTEwKICAgKlRFWFQgdGFnIE5PVCBOVUxMCiAgIFRFWFQgYXV0aG9yIE5PVCBOVUxMCiAgIElOVEVHRVIgY3JlYXRlZF9hdCBOT1QgTlVMTAogICBJTlRFR0VSIGtpbmQgTk9UIE5VTEwKfQpjbGFzcyBub3N0cl9yZWxheV9taWdyYXRpb25zewogKklOVEVHRVIgaWQKICAgSU5URUdFUiBjcmVhdGVkX2F0IE5PVCBOVUxMCiAgIFRFWFQgbmFtZSBOT1QgTlVMTAp9CmV2ZW50cyAiMSIgLS0gIjAuLm4iIGdlbmVyaWNfdGFncw==)
