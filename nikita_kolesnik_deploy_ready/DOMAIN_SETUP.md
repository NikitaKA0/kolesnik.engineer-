# Connecting `kolesnik.engineer` (Netlify)

The following is a preparation checklist, **not proof of registration or connection**. Domain registration and DNS updates require access to the owner’s account(s).

1. Confirm `kolesnik.engineer` is registered and you control it. If not, register it through a domain registrar.
2. Deploy the website to Netlify. Your site will initially have a generated `<site>.netlify.app` address.
3. In Netlify, go to **Domain management → Add a domain → Add a domain you already own**. Enter `kolesnik.engineer`.
4. Select whether to use Netlify DNS or External DNS. If you retain the registrar's DNS provider:
   - For root/apex `@`: if the provider supports `ALIAS`/`ANAME`/flattened `CNAME`, point to `apex-loadbalancer.netlify.com`. Otherwise, set an `A` record for `@` to `75.2.60.5`.
   - For `www`: set a `CNAME` to your **actual** `<site>.netlify.app` name (not literally the placeholder).
   - Remove conflicting root A/AAAA records where applicable, and keep existing mail MX/TXT records intact.
5. Check Netlify **Pending DNS verification** for the instructions **specific to your account/project**, then wait for DNS to propagate and HTTPS provisioning. Set the primary domain and preferred www redirect.
6. Test `https://kolesnik.engineer` and `https://www.kolesnik.engineer` from a browser. Do not update external QR codes until the site is actually reachable.

Official docs (current as of site preparation):
- https://docs.netlify.com/manage/domains/manage-domains/assign-a-domain-to-your-site-app/
- https://docs.netlify.com/manage/domains/configure-domains/configure-external-dns/

This archive does **not** register/purchase the domain or connect it.
