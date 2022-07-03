<template>
	<el-aside width="200px">
		
		<el-menu
		  default-active="2"
		  class="el-menu-vertical-demo" router>
			  
			 <el-menu-item index="/home">
			  <i class="el-icon-menu"></i>
			  <span slot="title">首页</span>
			</el-menu-item>
			
			<el-menu-item index="2">
			  <i class="el-icon-menu"></i>
			  <span slot="title">数据管理</span>
			</el-menu-item>
			
			
			<el-submenu index="3">
				<template slot="title">
				  <i class="el-icon-menu"></i>
				  <span>信息管理</span>
				</template>
				 
				  <el-menu-item index="1-1">列表管理1</el-menu-item>
				  <el-menu-item index="1-2">列表管理2</el-menu-item>
				
			 </el-submenu>

		</el-menu >
	</el-aside>
	
</template>
