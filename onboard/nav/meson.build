project('nav', 'cpp', default_options : ['cpp_std=c++14'])

liblcm = dependency('lcm')

executable('onboard_nav', 'main.cpp', 'stateMachine.cpp', 'rover.cpp', 'obstacle_avoidance/obstacleAvoidanceStateMachine.cpp', 'obstacle_avoidance/simpleAvoidance.cpp', 'pid.cpp', 'utilities.cpp',
			'search/spiralInSearch.cpp', 'search/lawnMowerSearch.cpp', 'search/searchStateMachine.cpp', 'search/spiralOutSearch.cpp',
           dependencies : [liblcm],
           install : true)
