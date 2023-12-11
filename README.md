# Intel-gyunggi2
## Intel-gyunggi2
### Intel-gyunggi2
#### Intel-gyunggi2

	  if(val != 1)
	  {
		  HAL_GPIO_TogglePin(LD2_GPIO_Port, LD2_Pin);
		  //HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1);
		  HAL_Delay(200);
		  //HAl_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);
		  //HAL_Delay(200);
		  //flag = 0;

	  }
	  else
		  HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);
