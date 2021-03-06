
Changelog
=========

`0.41.0 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.5...v0.41.0>`_ (2019-12-27)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **mac_shortcut.sh:** fix ``shellcheck`` error (\ `d538798 <https://github.com/saltstack-formulas/postgres-formula/commit/d538798ee4423ecb72b29bd39e4f35437412ce43>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `f3ec66d <https://github.com/saltstack-formulas/postgres-formula/commit/f3ec66d5ed90bc9a458fdff2233c9a707f0c9c72>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `a77bb06 <https://github.com/saltstack-formulas/postgres-formula/commit/a77bb06b18823c7db0debd2c4ff135a367f76d04>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `20e5e46 <https://github.com/saltstack-formulas/postgres-formula/commit/20e5e46e1011641714a11756617530b898e3d689>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `8080be6 <https://github.com/saltstack-formulas/postgres-formula/commit/8080be6be3dd0c8799fa102b1235fb151514bced>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `8ce1ee4 <https://github.com/saltstack-formulas/postgres-formula/commit/8ce1ee4ecc5dd6a6a14118eda75b3446b6f58d82>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `bd5959c <https://github.com/saltstack-formulas/postgres-formula/commit/bd5959c60a93e65ea0658f5cb7fd1609bdd3399c>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `0a2b63a <https://github.com/saltstack-formulas/postgres-formula/commit/0a2b63aba85b09c8983d066cbad7e344de791db1>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `f0d12ca <https://github.com/saltstack-formulas/postgres-formula/commit/f0d12caac67bf7f2049ca7f1b7185912e876cb02>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `1392538 <https://github.com/saltstack-formulas/postgres-formula/commit/1392538665bea2a699836a87a6b749e07276a94d>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `c9a57aa <https://github.com/saltstack-formulas/postgres-formula/commit/c9a57aa96bb80dc27c4722e0f8dc45c77460c03a>`_\ )

Features
^^^^^^^^


* **codenamemap:** update for current versions (\ `9cc95c0 <https://github.com/saltstack-formulas/postgres-formula/commit/9cc95c020909563486f404b186e15ed71dd8a83a>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `ccaf4e5 <https://github.com/saltstack-formulas/postgres-formula/commit/ccaf4e5e3729c75c3a5eccbf482e7fca09415fea>`_\ )

`0.40.5 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.4...v0.40.5>`_ (2019-10-28)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **macros.jinja:** apply suggestion from PR (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/d606b28>`_\ )
* **macros.jinja:** use ``user`` kwarg for schemas (required on FreeBSD) (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/7ff798a>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** add pre-salted ``FreeBSD-12.0`` box for local testing (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/eefb89e>`_\ )
* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/81b2c2e>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/62baac2>`_\ )

Documentation
^^^^^^^^^^^^^


* **contributing:** remove to use org-level file instead [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/5a291ab>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/e568f28>`_\ )

`0.40.4 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.3...v0.40.4>`_ (2019-10-11)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** add fixes using ``rubocop --safe-auto-correct`` (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/37b0c43>`_\ )
* **rubocop:** fix remaining errors manually (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/b369aa9>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/7822200>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/2c82872>`_\ )

`0.40.3 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.2...v0.40.3>`_ (2019-10-10)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **manage.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/bf5b4d6>`_\ )
* **python.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/1f3cfcc>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/7ca61f3>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/76e3e39>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/3a27978>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/89e4a34>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/postgres-formula/commit/a0fdd48>`_\ )

`0.40.2 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.1...v0.40.2>`_ (2019-09-13)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **freebsd:** no libpqdev freebsd package (\ `eca6d97 <https://github.com/saltstack-formulas/postgres-formula/commit/eca6d97>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `9796319 <https://github.com/saltstack-formulas/postgres-formula/commit/9796319>`_\ )

`0.40.1 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.40.0...v0.40.1>`_ (2019-09-11)
-------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `fc6cbe0 <https://github.com/saltstack-formulas/postgres-formula/commit/fc6cbe0>`_\ )

Documentation
^^^^^^^^^^^^^


* **pillar.example:** update examples for freebsd (\ `a799214 <https://github.com/saltstack-formulas/postgres-formula/commit/a799214>`_\ )

`0.40.0 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.39.1...v0.40.0>`_ (2019-09-03)
-------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **archlinux:** add support, fixing rendering errors (\ `e970925 <https://github.com/saltstack-formulas/postgres-formula/commit/e970925>`_\ )

`0.39.1 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.39.0...v0.39.1>`_ (2019-09-01)
-------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** replace EOL pre-salted images (\ `140928b <https://github.com/saltstack-formulas/postgres-formula/commit/140928b>`_\ )

Tests
^^^^^


* **inspec:** fix reference to ``suse`` after gem ``train`` update (\ `677adba <https://github.com/saltstack-formulas/postgres-formula/commit/677adba>`_\ )

`0.39.0 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.38.0...v0.39.0>`_ (2019-08-17)
-------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `1f0fd92 <https://github.com/saltstack-formulas/postgres-formula/commit/1f0fd92>`_\ )

`0.38.0 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.37.4...v0.38.0>`_ (2019-07-24)
-------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** remove ``python*-pip`` installation (\ `d999597 <https://github.com/saltstack-formulas/postgres-formula/commit/d999597>`_\ )
* **kitchen+travis:** modify matrix to include ``develop`` platform (\ `3f81439 <https://github.com/saltstack-formulas/postgres-formula/commit/3f81439>`_\ )

Features
^^^^^^^^


* **debian:** add buster support (\ `904ba27 <https://github.com/saltstack-formulas/postgres-formula/commit/904ba27>`_\ )

`0.37.4 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.37.3...v0.37.4>`_ (2019-05-31)
-------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** reduce matrix down to 6 instances (\ `2ff919f <https://github.com/saltstack-formulas/postgres-formula/commit/2ff919f>`_\ )

Tests
^^^^^


* **\ ``services_spec``\ :** remove temporary ``suse`` conditional (\ `81165fc <https://github.com/saltstack-formulas/postgres-formula/commit/81165fc>`_\ )
* **command_spec:** use cleaner ``match`` string using ``%r`` (\ `a054cea <https://github.com/saltstack-formulas/postgres-formula/commit/a054cea>`_\ )
* **locale:** improve test using locale ``en_US.UTF-8`` (\ `7796064 <https://github.com/saltstack-formulas/postgres-formula/commit/7796064>`_\ )

`0.37.3 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.37.2...v0.37.3>`_ (2019-05-16)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **freebsd-user:** fix FreeBSD daemon's user for PostgreSQL >= 9.6 (\ `8745365 <https://github.com/saltstack-formulas/postgres-formula/commit/8745365>`_\ ), closes `#263 <https://github.com/saltstack-formulas/postgres-formula/issues/263>`_

`0.37.2 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.37.1...v0.37.2>`_ (2019-05-12)
-------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **sysrc-svc:** workaround *BSD minion indefinitely hanging on start (\ `0aa8b4a <https://github.com/saltstack-formulas/postgres-formula/commit/0aa8b4a>`_\ )

`0.37.1 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.37.0...v0.37.1>`_ (2019-05-06)
-------------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** fix link for Travis badge (\ `850ca6a <https://github.com/saltstack-formulas/postgres-formula/commit/850ca6a>`_\ )

`0.37.0 <https://github.com/saltstack-formulas/postgres-formula/compare/v0.36.0...v0.37.0>`_ (2019-05-06)
-------------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **kitchen:** prefer ``kitchen.yml`` to ``.kitchen.yml`` (\ `8f7cbde <https://github.com/saltstack-formulas/postgres-formula/commit/8f7cbde>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** prepare for ``inspec`` testing (\ `157e169 <https://github.com/saltstack-formulas/postgres-formula/commit/157e169>`_\ )
* **kitchen:** use pre-salted images as used in ``template-formula`` (\ `611ec11 <https://github.com/saltstack-formulas/postgres-formula/commit/611ec11>`_\ )
* **kitchen+travis:** use newly available pre-salted images (\ `7b7aadc <https://github.com/saltstack-formulas/postgres-formula/commit/7b7aadc>`_\ )
* **pillar_from_files:** use custom pillar based on ``pillar.example`` (\ `c64d9e4 <https://github.com/saltstack-formulas/postgres-formula/commit/c64d9e4>`_\ )
* **travis:** add ``.travis.yml`` based on ``template-formula`` (\ `6467df7 <https://github.com/saltstack-formulas/postgres-formula/commit/6467df7>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** update ``Testing`` section for ``inspec`` (\ `4cfde8d <https://github.com/saltstack-formulas/postgres-formula/commit/4cfde8d>`_\ )

Features
^^^^^^^^


* implement ``semantic-release`` (\ `7d3aa19 <https://github.com/saltstack-formulas/postgres-formula/commit/7d3aa19>`_\ )

Tests
^^^^^


* **inspec:** add tests for multiple ports and postgres versions (\ `bf6a653 <https://github.com/saltstack-formulas/postgres-formula/commit/bf6a653>`_\ )
* **inspec:** enable ``use_upstream_repo`` for ``debian`` & ``centos-6`` (\ `49fdd33 <https://github.com/saltstack-formulas/postgres-formula/commit/49fdd33>`_\ )
* **inspec:** replace ``serverspec`` with ``inspec`` tests (\ `58ac122 <https://github.com/saltstack-formulas/postgres-formula/commit/58ac122>`_\ )
* **inspec:** use relaxed command output match for the time being (\ `3c53684 <https://github.com/saltstack-formulas/postgres-formula/commit/3c53684>`_\ )
