arraysetters
==================================================

# NAME

  arraysetters

# SYNOPSIS

Steps to produce package
 
 kpt cfg create-setter . trust-domains --type array --field spec.trustDomain --schema-path schema.json

 kpt cfg create-subst . trust-domain-sub --field-value PROJECT_ID.svc.id.goog --pattern \${gcloud.core.project}.svc.id.goog 

