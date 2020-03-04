# StARSlamPlugin类

**Slam相关接口说明**

### public int StartSlam()
        /// <summary>
        /// Start 3dof or 6dof alg and related sensors
        /// </summary>
        /// <returns>
        /// 0:  Send start command failed
        /// 1:  Send start command success
        /// -2019: This API not be supported in this device
        /// </returns>
		public int StartSlam()

### public int StopSlam()
        /// <summary>
        /// Stop 3dof or 6dof Alg and related sensors
        /// </summary>
        /// <returns>
        /// 0:  Send start command failed
        /// 1:  Send start command success
        /// -2019: This API not be supported in this device
        /// </returns>
		public int StopSlam()

### public int ResetSlam()
        /// <summary>
        /// Reset 6dof alg
        /// </summary>
        /// <returns>
        /// 0: Send reset command failed
        /// 1: Send reset command success
        /// -2019: This API not be supported in this device
        /// </returns>
		public int ResetSlam()

### public int SwitchSlamMode(bool mode)
        /// <summary>
        /// Switch slam work mode between 3dof and 6dof
        /// </summary>
        /// <param name="mode">
        ///  mode == true 6dof mode
        ///  mode == false 3dof mode
        /// </param>
        /// <returns>
        /// 0: Send set mode_switch command failed
        /// 1: Send set mode_switch command success
        /// -2019: This API not be supported in this device
        /// </returns>
		public int SwitchSlamMode(bool mode)

### public int intSlamInitStat()
        /// <summary>
        /// Get slam service initial status
        /// </summary>
        /// <returns>
        /// 0: slam service is initing
        /// 1: slam service initial finished and already work
        /// -2019: This API not be supported in this device
        /// </returns>
		public int intSlamInitStat()