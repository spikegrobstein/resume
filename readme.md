

    Spike Grobstein  |  me@spike.cx       |  908.803.8995
    Hoboken, NJ      |  spike.grobste.in  |  GitHub: spikegrobstein

## Objective

I like systems. I like programming languages. I like high performance. I like building tools and
making applications talk to each other. I like making things work.

## Skills

 * Linux (Debian/Ubuntu/Gentoo), OSX Server, BeOS, Windows 2003
 * Firewalls, Bind, Chef, nginx
 * PostgreSQL, MySQL, Redis, Marklogic Server
 * Ruby, C, Bash, Applescript, Python, PHP, XQuery, plpgsql, ObjC, Javascript, Perl, Java
 * Offset printing, color separations, color correction, screenprinting, embroidery
 * Certified Expert in Adobe Photoshop and Illustrator.

## Experience

**Ticket Evolution** - Jersey City, NJ - SaaS provider for online event ticket sales  
2012/01 - present / Sr DevOps Engineer

 * Profiled and optimized API through better SQL queries and better Ruby code
 * Refactored inventory importer to properly handle UTF8 and improve import performance dramatically
 * Led migration of production site from pure AWS infrastructure to local datacenter
 * Architected and implemented infrastructure in new environment with new deployment tools (capistrano),
   monitoring (scoutapp.com) and configuration management (Chef)
 * Built Scout plugins in Ruby for monitoring unsupported processes and services including alerts for
   customer balance tracking and internal Postgres metrics
 * Built Resque plugin (with monkey-patched Resque) for monitoring queue latency. Latency is defined as
   how long it took the last job in the queue to run from the time it was queued.

**Warner Music Group** - New York City, NY - Major Record Label  
2007/08 - 2011/12 / Digital Technology Architect

 * Architected and implemented application for collecting and reporting on data from the internet using
   Kapow, PHP (wrappers for collection agents), Rails (Frontend/CnC/Reporting), MySQL (orchestration
   datastore), Marklogic (online datastore), NEC HYDRAstor (offline/nearline storage of collected data),
   which ran for 2 years, saving and making the company millions of dollars every month.
 * Investigated and reverse engineered software for applications designed for copyright infringement
   (eg: Limewire, etc) to determine risk, technologies and extent of violations.
 * Determined and implemented procedures for video encoding server farm of XServes; built scripts to
   manage/audit versions of libraries and initial configuration of servers using Ruby, designed and
   documented procedures for NetRestore of servers.

**National Flag & Display** - New York City, NY - Flag and Banner production company  
2004/08 - 2007/08 / Production Artist

 * Automated workflow of Art Department using Perl, Bash and Applescript saving each artist hours per
   day and overall improving life in the art department. Automation included preflighting procedures
   and procedures for sending files to vendors (tagging, building PO and composing emails or burning
   CDs/DVDs)
 * Built FTP server for customers to upload artwork using Gentoo Linux. Included log parser (written in
   Perl) to notify of new uploads, seamless integration to their website with a web frontend for uploading
   files and including custom messages to the appropriate salesperson. Server ran for over 3 years
   unattended.
 * Redesigned and built the company's website using PHP and my own custom templating engine which
   brought in several dozen new orders per month over the first year it was up.
 * Built software for parsing, reporting and pointing out errors in EZPass statements for a subsidiary
   trucking company. Scraped EZPass website using Perl into CSV, built reports in Excel using VBA.

**Purnell School** - Pottersville, NJ - Alternative Girls Boarding High School  
2006/07 - 2012/10 / Contract Engineer

 * Designed and implemented ESX Server for hosting internal applications, consolidating 8 physical
   servers into a single unit.
 * Built a web application for tracking merits (points) of the students with dashboard so they can
   redeem them for prizes. Application was builtin Ruby on Rails with integration into ActiveDirectory
   authentication server using an LDAP gem. Supported over 250 users.
 * Implemented Moodle for student course management and homework tracking that tied into the same
   ActiveDirectory authentication server as the Merits app.
 * Built application in PHP that would seamlessly tie into Moodle and Merits to ease importation of
   new students via CSV file.
 * All above sites used the same look and feel as the school's intranet, leveraging modern HTML and
   CSS techniques and sharing templates.

*Additional Experience available on request*

## Noteworthy Side Projects

**Flatiron School** - `http://www.flatironschool.com`  
I've been invited for 3 consecutive classes to give a guest lecture on basic Linux systems administration
and application deployment. Lecture outline is available on my GitHub profile.

**mcwrapper** - `https://github.com/spikegrobstein/mcwrapper`  
A full-featured commandline tool built in Bash for managing a Minecraft Server. Wraps Minecraft Server
Java exectuable to enable offline commands using a FIFO and safe, atomic world data backups and restores.

**capistrano-mailgun** - `https://github.com/spikegrobstein/capistrano-mailgun`  
A Rubygem for sending notifications for Capistrano deployments via the Mailgun API.

**nesromtool** - `https://github.com/sadistech/nesromtool`  
A commandline tool built in C for hacking Nintendo (NES) ROMs. Cleanroom implementation from publically
available documentation. Allows one to replace programming or image content in ROMs.

**gcmtool** - `https://github.com/sadistech/gcmtool`  
A commandline tool built in C for hacking GameCube (GCM) ROMs. Mostly cleanroom implementation from
publicly available documentation. Involved some reverse engineering for unknown portions. Allows one
to read/write the filesystem of a ROM and extract/replace bootloader.

*Additional information available upon request*
