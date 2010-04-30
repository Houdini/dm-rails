source 'http://rubygems.org'

DATAMAPPER = 'git://github.com/datamapper'

group :runtime do

  git 'git://github.com/rails/rails.git' do

    gem 'activesupport', '~> 3.0.0.beta3', :require => 'active_support'
    gem 'actionpack',    '~> 3.0.0.beta3', :require => 'action_pack'
    gem 'railties',      '~> 3.0.0.beta3', :require => 'rails'

  end

  gem 'dm-core',         '~> 0.10.3', :git => "#{DATAMAPPER}/dm-core.git"
  gem 'dm-active_model', '~> 0.4',    :git => "#{DATAMAPPER}/dm-active_model.git"

end

group :development do

  gem 'rake',            '~> 0.8.7'
  gem 'jeweler',         '~> 1.4'
  gem 'yard',            '~> 0.5'

end

group :quality do # These gems contain rake tasks that check the quality of the source code

  gem 'yardstick',      '~> 0.1'
  gem 'metric_fu',      '~> 1.3'
  gem 'reek',           '~> 1.2.7'
  gem 'roodi',          '~> 2.1'

end
