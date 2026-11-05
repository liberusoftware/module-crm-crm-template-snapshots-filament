# Crm Template Snapshots · Laravel · Filament

Independent presentation module skeleton for **Crm Template Snapshots**. Intended boundary: php/composer laravel host with filament panels.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

- Capability/source key: `planned:crm:crm-template-snapshots`.
- Presentation scope: [Crm Template Snapshots](https://github.com/liberusoftware/documentation/blob/main/projects/crm/filament/crm-template-snapshots.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/crm/nextjs/crm-template-snapshots.md).
- Registry identity: `liberusoftware/crm-crm-template-snapshots-filament`.
- Foundation: [module-boilerplate-filament](https://github.com/liberusoftware/module-boilerplate-filament) at `9282e55622b1abd4db48da891480cd9cac46c158`.

## Develop and verify

```bash
composer install
composer validate --strict
composer check
```

The public entry is `Liberu\Presentation\Capability1a873fa1f3f2\CapabilityPlugin::make()`, registered explicitly by the consuming Filament panel. It supplies the plugin lifecycle and a unique ID; no resources, pages or domain behavior are registered yet. Configure the reviewed Liberu installer in the host for the declared module package type.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/README.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [CRM](https://github.com/liberusoftware/project-crm-laravel-filament): Relationships, sales pipelines and customer service.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-crm-crm-template-snapshots-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-crm-crm-template-snapshots-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-crm-crm-template-snapshots-nuxt).
- [Next.js · React](https://github.com/liberusoftware/module-crm-crm-template-snapshots-nextjs).
- [React Native · Expo](https://github.com/liberusoftware/module-crm-crm-template-snapshots-react-native).
- [Flutter · Mobile](https://github.com/liberusoftware/module-crm-crm-template-snapshots-flutter).
- [Dart · Desktop](https://github.com/liberusoftware/module-crm-crm-template-snapshots-dart-desktop).
- [Dart · Mobile](https://github.com/liberusoftware/module-crm-crm-template-snapshots-dart-mobile).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
