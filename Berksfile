#
# vim: set ft=ruby:
#

chef_api "https://chefdev.mkd2.ktc", node_name: "cookbook", client_key: ".cookbook.pem"

site :opscode

metadata

cookbook "collectd"
cookbook "graphite"

cookbook "ktc-testing"
cookbook "ktc-utils"
cookbook "collectd_test", path: "test/cookbooks/collectd_test"
