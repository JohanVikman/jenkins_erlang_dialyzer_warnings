jenkins_erlang_dialyzer_warnings
================================

This is intended to use together with the Log Parser plugin (https://wiki.jenkins-ci.org/display/JENKINS/Log+Parser+Plugin)
for Jenkins.

A set of regexpes for parsing dialyzer warnings.

You need to configure the log parser plugin

Jenkins -> Manage Jenkins -> Configure System -> Console Output Parsing

Add a rule and provide the full path to the parsing rule file. 
For example:  /usr/share/jenkins/log_parser_rules/erlang_dialyzer.rules
