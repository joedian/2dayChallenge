/**
 * 
 */
package com.joedianreid.n26.controller;

import org.springframework.http.HttpStatus;
import org.springframework.http.MediaType;
import org.springframework.web.bind.annotation.RequestBody;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestMethod;
import org.springframework.web.bind.annotation.ResponseBody;
import org.springframework.web.bind.annotation.ResponseStatus;
import org.springframework.web.bind.annotation.RestController;

import com.joedianreid.n26.models.Statistic;
import com.joedianreid.n26.models.Transaction;

@RestController
@RequestMapping(value = "/transactions")
public class TransactionController {
	
	@RequestMapping(value = "/posttransaction",
		    		method = RequestMethod.PUT,
		    		consumes = MediaType.APPLICATION_JSON_UTF8_VALUE)
	@ResponseStatus(code= HttpStatus.CREATED)
	@ResponseBody
	public Statistic createTransaction(@RequestBody Transaction transaction)
		    
		  {
		   
		    return new Statistic();
		  }

}
