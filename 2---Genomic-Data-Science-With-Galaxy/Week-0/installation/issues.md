```sh
dell@DELL3521 /c/python27
$ cd "/d"

dell@DELL3521 /d
$ git clone https://github.com/galaxyproject/galaxy/
Cloning into 'galaxy'...
remote: Counting objects: 173014, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 173014 (delta 0), reused 0 (delta 0), pack-reused 173012
Receiving objects: 100% (173014/173014), 55.04 MiB | 121.00 KiB/s, done.
Resolving deltas: 100% (137244/137244), done.
Checking connectivity... done.
Checking out files: 100% (3891/3891), done.

dell@DELL3521 /d
$ cd galaxy

dell@DELL3521 /d/galaxy (dev)
$ git checkout -b master origin/master
Checking out files: 100% (641/641), done.
Branch master set up to track remote branch master from origin.
Switched to a new branch 'master'

dell@DELL3521 /d/galaxy (master)
$ python --version
Python 3.4.3

dell@DELL3521 /d/galaxy (master)
$ alias python='/c/python27/python.exe'

dell@DELL3521 /d/galaxy (master)
$ python --version
Python 2.7.6

dell@DELL3521 /d/galaxy (master)
$ run.sh
Initializing config/migrated_tools_conf.xml from migrated_tools_conf.xml.sample
Initializing config/shed_tool_conf.xml from shed_tool_conf.xml.sample
Initializing config/shed_tool_data_table_conf.xml from shed_tool_data_table_conf
.xml.sample
Initializing config/shed_data_manager_conf.xml from shed_data_manager_conf.xml.s
ample
Initializing lib/tool_shed/scripts/bootstrap_tool_shed/user_info.xml from user_i
nfo.xml.sample
Initializing tool-data/shared/ucsc/builds.txt from builds.txt.sample
Initializing tool-data/shared/ucsc/ucsc_build_sites.txt from ucsc_build_sites.tx
t.sample
Initializing tool-data/shared/igv/igv_build_sites.txt from igv_build_sites.txt.s
ample
Initializing tool-data/shared/rviewer/rviewer_build_sites.txt from rviewer_build
_sites.txt.sample
Initializing tool-data/add_scores.loc from add_scores.loc.sample
Initializing tool-data/alignseq.loc from alignseq.loc.sample
Initializing tool-data/all_fasta.loc from all_fasta.loc.sample
Initializing tool-data/bfast_indexes.loc from bfast_indexes.loc.sample
Initializing tool-data/binned_scores.loc from binned_scores.loc.sample
Initializing tool-data/codingSnps.loc from codingSnps.loc.sample
Initializing tool-data/encode_datasets.loc from encode_datasets.loc.sample
Initializing tool-data/faseq.loc from faseq.loc.sample
Initializing tool-data/funDo.loc from funDo.loc.sample
Initializing tool-data/liftOver.loc from liftOver.loc.sample
Initializing tool-data/maf_index.loc from maf_index.loc.sample
Initializing tool-data/maf_pairwise.loc from maf_pairwise.loc.sample
Initializing tool-data/microbial_data.loc from microbial_data.loc.sample
Initializing tool-data/mosaik_index.loc from mosaik_index.loc.sample
Initializing tool-data/ngs_sim_fasta.loc from ngs_sim_fasta.loc.sample
Initializing tool-data/perm_base_index.loc from perm_base_index.loc.sample
Initializing tool-data/perm_color_index.loc from perm_color_index.loc.sample
Initializing tool-data/phastOdds.loc from phastOdds.loc.sample
Initializing tool-data/picard_index.loc from picard_index.loc.sample
Initializing tool-data/quality_scores.loc from quality_scores.loc.sample
Initializing tool-data/regions.loc from regions.loc.sample
Initializing tool-data/sequence_index_base.loc from sequence_index_base.loc.samp
le
Initializing tool-data/sequence_index_color.loc from sequence_index_color.loc.sa
mple
Initializing tool-data/sift_db.loc from sift_db.loc.sample
Initializing tool-data/srma_index.loc from srma_index.loc.sample
Initializing tool-data/twobit.loc from twobit.loc.sample
Initializing static/welcome.html from welcome.html.sample
Some eggs are out of date, attempting to fetch...
Fetched http://eggs.galaxyproject.org/Mako/Mako-0.4.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/repoze.lru/repoze.lru-0.6-py2.7.egg
Fetched http://eggs.galaxyproject.org/ordereddict/ordereddict-1.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/Fabric/Fabric-1.7.0-py2.7.egg
Fetched http://eggs.galaxyproject.org/Babel/Babel-1.3-py2.7.egg
Fetched http://eggs.galaxyproject.org/Whoosh/Whoosh-2.4.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/Parsley/Parsley-1.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/paramiko/paramiko-1.11.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/lrucache/lrucache-0.2-py2.7.egg
Fetched http://eggs.galaxyproject.org/sqlalchemy_migrate/sqlalchemy_migrate-0.9.
6-py2.7.egg
Fetched http://eggs.galaxyproject.org/NoseHTML/NoseHTML-0.4.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/pexpect/pexpect-2.4-py2.7.egg
Fetched http://eggs.galaxyproject.org/amqp/amqp-1.4.6-py2.7.egg
Fetched http://eggs.galaxyproject.org/PasteDeploy/PasteDeploy-1.5.0-py2.7.egg
Fetched http://eggs.galaxyproject.org/WebHelpers/WebHelpers-1.3-py2.7.egg
Fetched http://eggs.galaxyproject.org/bioblend/bioblend-0.5.2-py2.7.egg
Fetched http://eggs.galaxyproject.org/docutils/docutils-0.7-py2.7.egg
Fetched http://eggs.galaxyproject.org/kombu/kombu-3.0.24-py2.7.egg
Fetched http://eggs.galaxyproject.org/mock/mock-1.0.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/raven/raven-3.1.8-py2.7.egg
Fetched http://eggs.galaxyproject.org/Beaker/Beaker-1.4-py2.7.egg
Fetched http://eggs.galaxyproject.org/sqlparse/sqlparse-0.1.14-py2.7.egg
Fetched http://eggs.galaxyproject.org/NoseTestDiff/NoseTestDiff-0.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/poster/poster-0.8.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/wchartype/wchartype-0.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/Tempita/Tempita-0.5.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/ssh/ssh-1.7.14-py2.7.egg
Fetched http://eggs.galaxyproject.org/Routes/Routes-2.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/six/six-1.9.0-py2.7.egg
Fetched http://eggs.galaxyproject.org/decorator/decorator-3.1.2-py2.7.egg
Fetched http://eggs.galaxyproject.org/importlib/importlib-1.0.3-py2.7.egg
Fetched http://eggs.galaxyproject.org/WebOb/WebOb-0.8.5-py2.7.egg
Fetched http://eggs.galaxyproject.org/boto/boto-2.27.0-py2.7.egg
Fetched http://eggs.galaxyproject.org/Paste/Paste-1.7.5.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/python_daemon/python_daemon-1.5.5-py2.7.eg
g
Fetched http://eggs.galaxyproject.org/wsgiref/wsgiref-0.1.2-py2.7.egg
Fetched http://eggs.galaxyproject.org/SVGFig/SVGFig-1.1.6-py2.7.egg
Fetched http://eggs.galaxyproject.org/pytz/pytz-2013.9-py2.7.egg
Fetched http://eggs.galaxyproject.org/nose/nose-0.11.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/requests/requests-2.2.1-py2.7.egg
Fetched http://eggs.galaxyproject.org/anyjson/anyjson-0.3.3-py2.7.egg
Fetched http://eggs.galaxyproject.org/WebError/WebError-0.8a-py2.7.egg
Fetched http://eggs.galaxyproject.org/twill/twill-0.9-py2.7.egg
pysam 0.4.2 couldn't be downloaded automatically.  You can try
building it by hand with:
  python scripts/scramble.py -c config/galaxy.ini.sample -e pysam
Fetch failed.
Traceback (most recent call last):
  File "./scripts/paster.py", line 36, in <module>
    from galaxy.util.pastescript import serve
  File "d:\galaxy\lib\galaxy\util\__init__.py", line 12, in <module>
    import grp
ImportError: No module named grp

dell@DELL3521 /d/galaxy (master)
$ pip install pysam
←[33mYou are using pip version 6.1.1, however version 7.0.3 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.←[0m
Collecting pysam
  Downloading pysam-0.8.3.tar.gz (1.5MB)
←[K    100% |################################| 1.5MB 54kB/s eta 0:00:01
Installing collected packages: pysam
  Running setup.py install for pysam
    Complete output from command D:\python3.4.3\python.exe -c "import setuptools
, tokenize;__file__='C:\\Users\\dell\\AppData\\Local\\Temp\\pip-build-m740zmtj\\
pysam\\setup.py';exec(compile(getattr(tokenize, 'open', open)(__file__).read().r
eplace('\r\n', '\n'), __file__, 'exec'))" install --record C:\Users\dell\AppData
\Local\Temp\pip-33i0th7b-record\install-record.txt --single-version-externally-m
anaged --compile:
    running install
    running build
    running build_py
    creating build
    creating build\lib.win32-3.4
    creating build\lib.win32-3.4\pysam
    copying pysam\namedtuple.py -> build\lib.win32-3.4\pysam
    copying pysam\Pileup.py -> build\lib.win32-3.4\pysam
    copying pysam\version.py -> build\lib.win32-3.4\pysam
    copying pysam\__init__.py -> build\lib.win32-3.4\pysam
    creating build\lib.win32-3.4\pysam\include
    copying pysam\include\__init__.py -> build\lib.win32-3.4\pysam\include
    package init file 'htslib\__init__.py' not found (or not a regular file)
    package init file 'htslib\htslib\__init__.py' not found (or not a regular fi
le)
    package init file 'samtools\__init__.py' not found (or not a regular file)
    package init file 'samtools\win32\__init__.py' not found (or not a regular f
ile)
    copying pysam\calignmentfile.pxd -> build\lib.win32-3.4\pysam
    copying pysam\cbcf.pxd -> build\lib.win32-3.4\pysam
    copying pysam\cfaidx.pxd -> build\lib.win32-3.4\pysam
    copying pysam\chtslib.pxd -> build\lib.win32-3.4\pysam
    copying pysam\csamfile.pxd -> build\lib.win32-3.4\pysam
    copying pysam\csamtools.pxd -> build\lib.win32-3.4\pysam
    copying pysam\ctabix.pxd -> build\lib.win32-3.4\pysam
    copying pysam\cvcf.pxd -> build\lib.win32-3.4\pysam
    copying pysam\TabProxies.pxd -> build\lib.win32-3.4\pysam
    copying pysam\htslib_util.h -> build\lib.win32-3.4\pysam
    copying pysam\pysam_stream.h -> build\lib.win32-3.4\pysam
    copying pysam\pysam_util.h -> build\lib.win32-3.4\pysam
    copying pysam\samfile_util.h -> build\lib.win32-3.4\pysam
    copying pysam\tabix_util.h -> build\lib.win32-3.4\pysam
    creating build\lib.win32-3.4\pysam\include\htslib
    copying htslib\config.h -> build\lib.win32-3.4\pysam\include\htslib
    copying htslib\hfile_internal.h -> build\lib.win32-3.4\pysam\include\htslib
    copying htslib\version.h -> build\lib.win32-3.4\pysam\include\htslib
    creating build\lib.win32-3.4\pysam\include\htslib\htslib
    copying htslib\htslib\bgzf.h -> build\lib.win32-3.4\pysam\include\htslib\hts
lib
    copying htslib\htslib\faidx.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\hfile.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\hts.h -> build\lib.win32-3.4\pysam\include\htslib\htsl
ib
    copying htslib\htslib\hts_defs.h -> build\lib.win32-3.4\pysam\include\htslib
\htslib
    copying htslib\htslib\kfunc.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\khash.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\khash_str2int.h -> build\lib.win32-3.4\pysam\include\h
tslib\htslib
    copying htslib\htslib\klist.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\knetfile.h -> build\lib.win32-3.4\pysam\include\htslib
\htslib
    copying htslib\htslib\kseq.h -> build\lib.win32-3.4\pysam\include\htslib\hts
lib
    copying htslib\htslib\ksort.h -> build\lib.win32-3.4\pysam\include\htslib\ht
slib
    copying htslib\htslib\kstring.h -> build\lib.win32-3.4\pysam\include\htslib\
htslib
    copying htslib\htslib\regidx.h -> build\lib.win32-3.4\pysam\include\htslib\h
tslib
    copying htslib\htslib\sam.h -> build\lib.win32-3.4\pysam\include\htslib\htsl
ib
    copying htslib\htslib\synced_bcf_reader.h -> build\lib.win32-3.4\pysam\inclu
de\htslib\htslib
    copying htslib\htslib\tbx.h -> build\lib.win32-3.4\pysam\include\htslib\htsl
ib
    copying htslib\htslib\vcf.h -> build\lib.win32-3.4\pysam\include\htslib\htsl
ib
    copying htslib\htslib\vcfutils.h -> build\lib.win32-3.4\pysam\include\htslib
\htslib
    copying htslib\htslib\vcf_sweep.h -> build\lib.win32-3.4\pysam\include\htsli
b\htslib
    creating build\lib.win32-3.4\pysam\include\samtools
    copying samtools\bam.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\bam2bcf.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\bam_endian.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\bam_lpileup.h -> build\lib.win32-3.4\pysam\include\samtools

    copying samtools\bam_plbuf.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\bam_tview.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\errmod.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\kprobaln.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\pysam.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\sam.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\sample.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\samtools.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\sam_header.h -> build\lib.win32-3.4\pysam\include\samtools
    copying samtools\stats_isize.h -> build\lib.win32-3.4\pysam\include\samtools

    copying samtools\version.h -> build\lib.win32-3.4\pysam\include\samtools
    creating build\lib.win32-3.4\pysam\include\samtools\win32
    copying samtools\win32\xcurses.h -> build\lib.win32-3.4\pysam\include\samtoo
ls\win32
    copying samtools\win32\zconf.h -> build\lib.win32-3.4\pysam\include\samtools
\win32
    copying samtools\win32\zlib.h -> build\lib.win32-3.4\pysam\include\samtools\
win32
    Fixing build\lib.win32-3.4\pysam\namedtuple.py build\lib.win32-3.4\pysam\Pil
eup.py build\lib.win32-3.4\pysam\version.py build\lib.win32-3.4\pysam\__init__.p
y build\lib.win32-3.4\pysam\include\__init__.py
    Skipping implicit fixer: buffer
    Skipping implicit fixer: idioms
    Skipping implicit fixer: set_literal
    Skipping implicit fixer: ws_comma
    Fixing build\lib.win32-3.4\pysam\namedtuple.py build\lib.win32-3.4\pysam\Pil
eup.py build\lib.win32-3.4\pysam\version.py build\lib.win32-3.4\pysam\__init__.p
y build\lib.win32-3.4\pysam\include\__init__.py
    Skipping implicit fixer: buffer
    Skipping implicit fixer: idioms
    Skipping implicit fixer: set_literal
    Skipping implicit fixer: ws_comma
    running build_ext
    Traceback (most recent call last):
      File "<string>", line 1, in <module>
      File "C:\Users\dell\AppData\Local\Temp\pip-build-m740zmtj\pysam\setup.py",
 line 498, in <module>
        dist = setup(**metadata)
      File "D:\python3.4.3\lib\distutils\core.py", line 148, in setup
        dist.run_commands()
      File "D:\python3.4.3\lib\distutils\dist.py", line 955, in run_commands
        self.run_command(cmd)
      File "D:\python3.4.3\lib\distutils\dist.py", line 974, in run_command
        cmd_obj.run()
      File "D:\python3.4.3\lib\site-packages\setuptools\command\install.py", lin
e 61, in run
        return orig.install.run(self)
      File "D:\python3.4.3\lib\distutils\command\install.py", line 539, in run
        self.run_command('build')
      File "D:\python3.4.3\lib\distutils\cmd.py", line 313, in run_command
        self.distribution.run_command(command)
      File "D:\python3.4.3\lib\distutils\dist.py", line 974, in run_command
        cmd_obj.run()
      File "D:\python3.4.3\lib\distutils\command\build.py", line 126, in run
        self.run_command(cmd_name)
      File "D:\python3.4.3\lib\distutils\cmd.py", line 313, in run_command
        self.distribution.run_command(command)
      File "D:\python3.4.3\lib\distutils\dist.py", line 974, in run_command
        cmd_obj.run()
      File "D:\python3.4.3\lib\site-packages\setuptools\command\build_ext.py", l
ine 50, in run
        _build_ext.run(self)
      File "D:\python3.4.3\lib\distutils\command\build_ext.py", line 308, in run

        force=self.force)
      File "D:\python3.4.3\lib\distutils\ccompiler.py", line 1031, in new_compil
er
        return klass(None, dry_run, force)
      File "D:\python3.4.3\lib\distutils\cygwinccompiler.py", line 282, in __ini
t__
        CygwinCCompiler.__init__ (self, verbose, dry_run, force)
      File "D:\python3.4.3\lib\distutils\cygwinccompiler.py", line 126, in __ini
t__
        if self.ld_version >= "2.10.90":
    TypeError: unorderable types: NoneType() >= str()

    ----------------------------------------
←[31m    Command "D:\python3.4.3\python.exe -c "import setuptools, tokenize;__fi
le__='C:\\Users\\dell\\AppData\\Local\\Temp\\pip-build-m740zmtj\\pysam\\setup.py
';exec(compile(getattr(tokenize, 'open', open)(__file__).read().replace('\r\n',
'\n'), __file__, 'exec'))" install --record C:\Users\dell\AppData\Local\Temp\pip
-33i0th7b-record\install-record.txt --single-version-externally-managed --compil
e" failed with error code 1 in C:\Users\dell\AppData\Local\Temp\pip-build-m740zm
tj\pysam←[0m

dell@DELL3521 /d/galaxy (master)
$ run.sh
Some eggs are out of date, attempting to fetch...
Warning: MarkupSafe (a dependent egg of Mako) cannot be fetched
Warning: pycrypto (a dependent egg of Fabric) cannot be fetched
Fetched http://eggs.galaxyproject.org/paramiko/paramiko-1.11.1-py2.7.egg
One of Galaxy's managed eggs depends on something which is missing, this is alm
st certainly a bug in the egg distribution.
Dependency "paramiko" requires "pycrypto>=2.1,!=2.4"
Traceback (most recent call last):
  File "./scripts/fetch_eggs.py", line 46, in <module>
    c.resolve() # Only fetch eggs required by the config
  File "d:\galaxy\lib\galaxy\eggs\__init__.py", line 396, in resolve
    egg.resolve()
  File "d:\galaxy\lib\galaxy\eggs\__init__.py", line 196, in resolve
    dists = pkg_resources.working_set.resolve( ( self.distribution.as_requireme
t(), ), env, self.fetch )
  File "d:\galaxy\lib\pkg_resources.py", line 569, in resolve
    raise VersionConflict(dist,req) # XXX put more info here
pkg_resources.VersionConflict: (paramiko 1.11.1 (d:\galaxy\eggs\paramiko-1.11.1
py2.7.egg), Requirement.parse('pycrypto>=2.1,!=2.4'))
Fetch failed.
Traceback (most recent call last):
  File "./scripts/paster.py", line 36, in <module>
    from galaxy.util.pastescript import serve
  File "d:\galaxy\lib\galaxy\util\__init__.py", line 12, in <module>
    import grp
ImportError: No module named grp

dell@DELL3521 /d/galaxy (master)
$ cd bx-python

dell@DELL3521 /d/galaxy/bx-python (master)
$ python --version
Python 2.7.6

dell@DELL3521 /d/galaxy/bx-python (master)
$ python setup.py
Downloading http://pypi.python.org/packages/source/d/distribute/distribute-0.6.3
5.tar.gz
Extracting in c:\users\dell\appdata\local\temp\tmpqxz7lr
Now working in c:\users\dell\appdata\local\temp\tmpqxz7lr\distribute-0.6.35
Building a Distribute egg in d:\galaxy\bx-python
d:\galaxy\bx-python\distribute-0.6.35-py2.7.egg
no previously-included directories found matching 'doc\.build'

Installed d:\galaxy\bx-python\nose-1.3.7-py2.7.egg
usage: setup.py [global_opts] cmd1 [cmd1_opts] [cmd2 [cmd2_opts] ...]
   or: setup.py --help [cmd1 cmd2 ...]
   or: setup.py --help-commands
   or: setup.py cmd --help

error: no commands supplied

dell@DELL3521 /d/galaxy/bx-python (master)
$ cd "/d/galaxy/pysqlite-2.5.6"

dell@DELL3521 /d/galaxy/pysqlite-2.5.6 (master)
$ python setup.py
usage: setup.py [global_opts] cmd1 [cmd1_opts] [cmd2 [cmd2_opts] ...]
   or: setup.py --help [cmd1 cmd2 ...]
   or: setup.py --help-commands
   or: setup.py cmd --help

error: no commands supplied

dell@DELL3521 /d/galaxy/pysqlite-2.5.6 (master)
$ cd "/d/galaxy/Cheetah-2.2.2"

dell@DELL3521 /d/galaxy/Cheetah-2.2.2 (master)
$ python setup.py
Not using setuptools, so we cannot install the Markdown dependency
usage: setup.py [global_opts] cmd1 [cmd1_opts] [cmd2 [cmd2_opts] ...]
   or: setup.py --help [cmd1 cmd2 ...]
   or: setup.py --help-commands
   or: setup.py cmd --help

error: no commands supplied
