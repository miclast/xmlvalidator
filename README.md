# xmlvalidator
Ruby based console XML validator

#!/usr/bin/env ruby
require 'nokogiri' ; xml = File.open(ARGV[0]) ; doc = Nokogiri::XML(xml) ; pp doc.errors
